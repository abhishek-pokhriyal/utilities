# utilities


1. List all unique extensions for files contained in a directory

    ```
    find . -type f | sed -En 's|.*/[^/]+\.([^/.]+)$|\1|p' | sort -u
    ```
  
    (Source: https://superuser.com/a/232101)
