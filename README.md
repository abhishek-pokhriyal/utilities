# utilities


1. List all unique extensions for files contained in a directory

    ```
    find . -type f | sed -En 's|.*/[^/]+\.([^/.]+)$|\1|p' | sort -u
    ```
  
    (Source: https://superuser.com/a/232101)
    

1. Recursively delete all files of a certain extension from a directory

    ```
    find UPMOST_RELEVANT_PATH -name ".ext" -delete
    ```
  
    (Source: https://superuser.com/a/89415)
    
    
    
    
    
    
