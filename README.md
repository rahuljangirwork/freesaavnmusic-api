# JioSaavn API (Unofficial)

An **unofficial API** for downloading high-quality songs, albums, playlists, and more from **JioSaavn**.

This project is built using **Bun**, a fast JavaScript runtime, and is deployed on **Cloudflare Workers** for low-latency, global distribution.

## 📚 Documentation

For detailed information on how to use the API, check out the [API documentation](docs/API.md).

## 🚀 Running Locally

You can easily set up the project locally for development or testing purposes.

### Prerequisites

1. **Install Bun**:  
   Bun is the JavaScript runtime and package manager. Follow the installation instructions from the official website: [Bun](https://bun.sh/).

2. **Clone the repository**:
   ```bash
   git clone https://github.com/rahuljangirwork/freesaavnmusic-api
   cd freesaavnmusic-api


### Install dependencies:

1. **Install dependencies**:  
   ```bash
   bun install

2. **Run the development server**:
   ```bash
   bun run dev



### Building for Deployment

**Before deploying your project, make sure to build it:**

```bash
bun run build
```

This will compile the TypeScript code into JavaScript in the dist/ folder.

### Deploying to Cloudflare Workers
You can deploy this project on Cloudflare Workers for global performance optimization.

1. Install Wrangler (Cloudflare CLI Tool)
Wrangler is the CLI tool to manage and deploy Cloudflare Workers. Install it globally:

```bash
npm install -g wrangler
```
2. Log in to Cloudflare
Authenticate Wrangler with your Cloudflare account:

```bash
wrangler login
```
3. Deploy to Cloudflare Workers
Deploy the project using Wrangler:

```bash
wrangler deploy
```
After deployment, Cloudflare will provide a live URL, for example:
https://your-project-name.cloudflareworkers.com




