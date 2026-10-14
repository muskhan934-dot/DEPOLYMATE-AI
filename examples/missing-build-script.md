# Example: Missing Build Script

## Problem
Deployment fails with the error: Missing script: "build".

## Diagnosis
The deployment command may not match the scripts defined in package.json.

## Steps to Fix
1. Open package.json if the project uses JavaScript.
2. Inspect the scripts section.
3. Identify the framework and build tool.
4. Check the hosting platform's build command.
5. Make the smallest necessary correction.
6. Run the appropriate build command again.

## Verification
Inspect the build output and deployment logs. Do not claim success without verification.

## Safety
Never request passwords, API keys, or other secrets. Do not blindly replace project configuration.
