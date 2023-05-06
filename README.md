# 21percenters
Decentralized ad brand using nostr to authenticate users, sign events, and push lightning payments.
System Overview for a Decentralized Ad Brand
Nostr Protocol Setup:
Enable user authentication and event signing.
Prevent duplicate usernames.
Implement unique login links and browser session persistence.
User Role Selection:
Allow users to choose one of the four roles: Advertiser, Promoter, Recruiter, or Client.
Advertiser Role:
Enable content posting (text, images, videos) using Nostr, Imgur, and Odysee.
Allow ad form creation with fields for ad title, description, call-to-action parameters, and specified reward.
Provide access to subscriber email addresses and usernames for internal marketing or membership programs.
Allow advertisers to host multiple channels under the same Nostr ID.
Promoter Role:
Enable promoters to host ad channels from a database of available ad channels.
Allow promoters to create multiple channels with different advertiser channels.
Recruiter Role:
Provide tools to showcase the value proposition of the platform.
Enable recruiters to direct potential advertisers to the platform for sign up.
Client Role:
Display a chronological timeline of subscribed ad channels.
Enable direct messaging with ad brands using Matrix.org protocol.
Allow clients to submit proofs of purchase and referral information.
Implement a system for automatic tracking of fulfilled calls-to-action.
Integration with GetAlby and Lightning Network:
Automatically create and manage Lightning Wallets and Addresses for users.
Enable Zap function to send microtransactions for fulfilled calls-to-action.
Tracking and Reward System:
Implement automatic tracking of user activity and rewards.
Generate weekly Lightning invoices for advertisers.
This system overview outlines the steps necessary to create a decentralized advertising platform with multiple user roles, content posting, and payment processing using Nostr, IPFS, and GetAlby. By following these guidelines, it is possible to create a platform that enables users to engage with advertising content, promote brands, and receive rewards in a decentralized and efficient manner.
