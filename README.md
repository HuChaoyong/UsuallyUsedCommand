# UsuallyUsedCommand
UsuallyUsedCommand


# Ubuntu

* enable root user
    ```bash
    sudo passwd root
    ```
* disabled root user

    ```bash
    sudo passwd -l root
    ```

# Docker

* list all container

    ```bash
    docker ps -a
    ```

* list all images

    ```bash
    docker images -a
    ```

* use dockerfile built on remote server

    ```bash
    docker -H tcp://192.168.1.24:2375 build -t blog/190320 .
    ```

* built container with alias

    ```bash
    docker run --name myBlog -d -p 8082:8080 4b22a4f3c322
    # 4b22a4f3c322 is images id
    ```