Make GitHub account.
Make an empty repo.
commit on local system.
Then to push on GitHub:
    1. git remote add origin [URL].
    2. git config --global user.name "[User Name]".
    3. git config --global user.email "[User Email]".
    4. git push u origin main
        - Will ask user name: same as set above.
        - Will ask password: Earlier the set password but ab you have tor create a personal access token (PAT), then copy the generated token link and paste in place of password.
    5. To generate token:
        - setting -> developer settings -> Personal Access Token -> Toke classic -> generate new token -> generate new token (classic) -> write note -> then select all or select as per your suitability.

