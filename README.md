# Playing Counter-Strike on Zorin OS

This guide provides step-by-step instructions to install and play
**Counter-Strike** on Zorin OS.

------------------------------------------------------------------------

## 1. Install Steam

1.  Open **Zorin Menu** → **Software**.
2.  Search for **Steam** and click **Install**.
3.  After installation, open Steam and log in with your account.

------------------------------------------------------------------------

## 2. Enable Steam Play (Proton)

1.  Open **Steam** → **Settings** → **Steam Play**.
2.  Check **Enable Steam Play for supported titles**.
3.  (Optional) Check **Enable Steam Play for all other titles** to play
    non-native games.
4.  Select the latest **Proton** version from the dropdown menu.

------------------------------------------------------------------------

## 3. Install Counter-Strike

1.  In the Steam store, search for **Counter-Strike** (1.6, Source, or
    Global Offensive).
2.  Click **Install**.
3.  Wait for the installation to complete.

------------------------------------------------------------------------

## 4. Launch the Game

1.  Open your Steam Library.
2.  Select **Counter-Strike** and click **Play**.
3.  If asked, allow Steam to run the game with **Proton**.

------------------------------------------------------------------------

## 5. Troubleshooting

-   If the game doesn't launch, try switching to another **Proton
    version** from Steam Play settings.

-   Ensure your **graphics drivers** are up to date (NVIDIA/AMD/Intel).

-   Run Steam from the terminal for error logs:

    ``` bash
    steam
    ```

------------------------------------------------------------------------

## 6. Optional: Optimize Performance

-   Use **GameMode** for better performance:

    ``` bash
    sudo apt install gamemode
    ```

-   Launch Counter-Strike with GameMode:

    ``` bash
    gamemoderun %command%
    ```

------------------------------------------------------------------------

## ENJOY CS on Zorin OS!
