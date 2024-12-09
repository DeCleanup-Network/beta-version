# beta-version
## DeCleanup V2
### Objective:
Upgrade the [DeCleanup dApp](https://decleanup.net) to V2, introducing enhanced functionality, improved scalability, and a more decentralized, user-driven experience. The key focus areas for the upgrade include:
- Transaction handling to shift interactions from admin-triggered to user-driven.
- Proof of Impact (PoI) enhancements with GEO tagging, timestamp integration, and additional metadata.
- Dynamic metadata system for tokenized cleanup efforts.
- Introduction of new user engagement features such as streak tracking, referral programs, and leaderboards.
### Current Platform State
**Current Chain** - Arbitrum
**Current User Flow**: check out [DeCleanup User Guide](https://paragraph.xyz/@decleanupnet/your-manual-on-decleanup-rewards)
**Verification System**:
Users submit their Proof of Impact (PoI) by uploading a photo via the dApp. The process is as follows:
The photo is stored on IPFS and linked to a Telegram bot for admin review.
The admin verifies the PoI and processes the transaction:
First Submission:
The admin copies the user’s wallet address and manually whitelists it.
The user then returns to the dApp to claim their reward, triggering a transaction from their wallet.
Subsequent Submissions:
The admin upgrades the associated token ID (leveling up to a maximum of 10 levels).
This transaction is triggered from the admin’s wallet, which creates scalability and decentralization challenges.
**Issue**:
The current system relies heavily on the admin wallet for most transactions, leading to bottlenecks and reduced decentralization. The system needs to transition to user-initiated transactions for alignment with blockchain principles.
### Desired Metadata Information for Dynamic Assets
The DeCleanup dynamic collection will reflect tokenized cleanup efforts with the following metadata:
**Developer**: EcoSynthesisX.eth.
**Collection Type**: Dynamic Tokenized Impact
**Traits**:
Category: Cleanup Impact Product
Impact: Environmental
Type: Dynamic assets with future staking utility.
DCU Points: Varies based on level (e.g., 10 for Newbie, 100 for Guardian).
Impact Value (IV): Varies based on level (e.g., 1 for Newbie, 10 for Guardian).
Level: User progression reflected dynamically (e.g., Newbie, Pro, Hero, Guardian).
### Goals for V2
**1. Multichain Compatibility:**
Explore multichain support starting with Supra L1 Move, if feasible.
**2. Proof of Impact (PoI) Enhancements**
Enhance submission data by including GEO location and timestamp information.
**3. User-Driven Transactions**
Transition all interactions, including PoI submissions and level upgrades, to be initiated by users rather than admins.
**4. Dynamic Metadata Updates**
Automatically update token metadata to reflect changes in Impact Value (IV), DCU Points, and user level upon approval of PoI submissions.
**5. Referral System**
Introduce referral links for users to share with their audience.
Reward users with an additional 5 DCU Points for every new user referred who registers and submits their first PoI.
**6. Leaderboard Implementation**
Showcase the 10 most active users on a public leaderboard.
Metrics for ranking include:
Total cleanups completed.
Level/Impact Value accumulated.
DCU Points earned.
Streak achievements and referred users.
**7. Streak System**
Track and reward users for consecutive cleanup submissions:
Additional DCU Points for reaching key levels (e.g., 3, 6, 9).
Reflect streak progress in the user’s dashboard and leaderboard standings.
**8. UI/UX Enhancements**
Introduce a dashboard with:
User’s level.
Current Impact Value and DCU Points.
IRL Impact Rank and streak progress.
Add a bug reporting feature and links to the user guide, Telegram, and X.
**9. X Connect Feature**
Enable users to share their minted NFT directly to their X profile with pre-formatted text (will be provided) for enhanced visibility. Create the minimum permissions the possible.
**10. Analytics Integration**
Collect dApp usage data to monitor engagement and optimize user experience.
**Optional/Later Features**
**1. Sponsored Transactions:**
Implement user-driven transactions where gas fees are covered by a sponsor wallet rather than the user.
### Proposed User Flow (Goals for V2)
**Onboarding:**
Users connect their wallet and optionally their X account.
Users are assigned a Newbie level with default values (IV = 0, DCU = 0, IRL Rank = 0).
**Cleanup Submission:**
Users upload PoI with GEO tagging and timestamp.
Upon verification, the system automatically updates token metadata to reflect rewards:
DCU Points, Impact Value, and Level (e.g., Newbie → Pro).
**Referral Program:**
Users share referral links to invite others.
Both the referrer and referee receive rewards upon successful participation.
**Leaderboards and Streaks:**
Users can track their standing and streak progress in the leaderboard.
Streak-based bonuses incentivize frequent participation.
