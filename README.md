# MyClient

MyClient is a desktop client for Minecraft Java Edition.

## Microsoft sign-in

The client lets a user sign in with their own Microsoft account to use their legitimately owned Minecraft Java Edition account.

Authentication uses Microsoft's official OAuth 2.0 Device Code Flow. The client never asks for, collects, or stores a user's Microsoft password.

## Data handling

The client uses authentication data only to create and refresh the signed-in user's local Minecraft session.

Authentication tokens are stored locally on the user's device and are not sent to third parties. No account passwords are collected.

This project is not affiliated with or endorsed by Microsoft or Mojang.
