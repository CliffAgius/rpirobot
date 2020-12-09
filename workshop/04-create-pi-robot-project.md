# Create Raspberry Pi Robot Project #

- Enter the Share Directory;

    ```
    cd /home/pi/share
    ```

- Create Pi Robot Project;

    ```
    dotnet new console -o rpirobot
    ```

- Set the permissions on the new directory so we can access it remotely;

    ```
    chmod 777 -R rpirobot
    ```

- Enter the Pi Robot directory;

    ```
    cd rpirobot
    ```

- Test the project runs

    ```
    dotnet run
    ```

<p align="center">
    <img src="images/04-hello-world.png" width="500px" >
</p>

| Previous | Next |
| -------- | ---- |
| [< Step 3 - Install .NET 5](03-install-dot-net-5.md) | [Step 5 - Build the Circuit - LED and Button >](05-build-circuit-led-and-button.md) |