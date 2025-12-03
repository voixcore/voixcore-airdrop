# VoixCore Airdrop App

This is the standalone Airdrop application for VoixCore.

## Deployment to Vercel

1.  **Download this folder** (`voixcore-airdrop`).
2.  **Push to GitHub**: Create a new repository and push this code.
3.  **Import to Vercel**:
    *   Go to Vercel Dashboard.
    *   Click "Add New..." -> "Project".
    *   Import your GitHub repository.
    *   Framework Preset: **Next.js**.
    *   Root Directory: `./` (default).
    *   Click **Deploy**.

## Configuration

*   **RPC URL**: The app connects to `https://explorer.voixcore.xyz/api/rpc`.
    *   **IMPORTANT**: Ensure your Cloudflare SSL mode for `explorer.voixcore.xyz` is set to **Flexible** so that the Vercel app (HTTPS) can communicate with the Explorer.

## Features

*   **Connect Wallet**: Metamask integration.
*   **Check Eligibility**: Verifies if the address has already claimed.
*   **Claim Airdrop**: Executes the `claim()` function on the smart contract.
*   **Real-time Stats**: Displays total claimed amount and participant count.
