
# MoveDIDBooster

Welcome to **MoveDIDBooster**, a Twitter-native AI agent designed to energize the Movement Network community by guiding users to create decentralized identities (DIDs) tied to their Twitter usernames. Built for the **Movement mAInia Hackathon**, this project combines the power of ElizaOS, Fleek deployment, and the MoveDID protocol to bridge Twitter and the blockchain in a fun, engaging way.

## Project Overview
MoveDIDBooster is your cheerful companion in the Movement ecosystem. It listens for tweets, responds with personalized hype, and directs users to the DID Activation Portal to create their on-chain MoveDIDs. Whether you're a builder, hacker, or fan, MoveDIDBooster celebrates your role in the community and makes DID creation a Twitter-driven adventure.

## Workflow
Here’s how MoveDIDBooster works:
1. **Engage Users on Twitter**: Responds to tweets like “`@MoveDIDBooster` give me a MoveDID” with enthusiasm and actionable guidance.
2. **User Tweets**: “`@MoveDIDBooster` give me a MoveDID.”
3. **AI Agent Listens**: The agent monitors Twitter for requests directed at `@MoveDIDBooster`.
4. **Personalized Response**: Crafts a hype-filled reply with a link to the DID Activation Portal, e.g., `https://movedidbooster.vercel.app/?description=[username]`.
   - Example: “@UserX, your VIP pass to a MoveDID awaits! Activate it at https://movedidbooster.vercel.app/?description=@UserX—join the Movement elite!”
5. **Redirect to Portal**: Users click the link and land on the DID Activation Portal (see [UI Repo](https://movedidbooster.vercel.app/)).
6. **DID Creation**: On the portal, users see their Twitter username pre-filled in the description field and follow simple guidelines to connect their wallet and create their DID.

## DID Activation Portal
- **Live URL**: [https://movedidbooster.vercel.app/](https://movedidbooster.vercel.app/)
- **Repo**: [MoveDIDBooster UI](https://github.com/thopatevijay/MoveDID/tree/main/manager-dapp)  
The portal is a customized fork of the [Manager-dApp](https://github.com/NonceGeek/MoveDID/tree/main/manager-dapp), branded with "Powered by MoveDIDBooster" and tailored to pre-fill Twitter usernames for a seamless experience.

## Setup
1. **Clone the Repo**: `git clone https://github.com/thopatevijay/MoveDIDBooster.git`
2. **Install Dependencies**: `pnpm install`  => "Node.js 23+ "
3. **Configure Environment**: Add your Twitter API keys and ElizaOS settings in `.env`.
4. **Run Locally**: `pnpm start`

## Future Enhancements
MoveDIDBooster is just the beginning! Here are planned improvements:
- **Twitter-Native DID Creation**: Implement a mechanism where users can create their MoveDID directly on Twitter by interacting with the agent, eliminating the UI redirect. This could leverage signed messages or Twitter-specific workflows for a fully social experience.
- **DID Creation Notifications**: Add a feature to notify users on Twitter when their DID is created (e.g., “@UserX, your MoveDID is live! Check it: [testnet link]”), boosting visibility and engagement across the Movement community on social media.
- **Community Gamification**: Introduce Twitter polls or hashtag campaigns to make DID creation a collective, fun event, enhancing its social impact.
- **Real-Time Monitoring**: Integrate blockchain listeners to automatically detect and tweet DID creation confirmations without manual intervention.

## Why MoveDIDBooster?
- **Community Focus**: Hypes up users and ties their Twitter identity to the Movement blockchain.
- **Hackathon Fit**: Aligns with the Social Intelligence Track and Fleek Bounty by delivering a Twitter-driven, AI-powered solution.
- **Scalability**: Starts simple but has a clear roadmap for innovative, on-chain enhancements.

Built with ❤️ for the Movement mAInia Hackathon, Feb 2025.