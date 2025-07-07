# ⛓️ 6 NFT CONTRACTS

## Purpose
The blockchain backbone - smart contracts that immortalize Biblical characters on Cardano

## What Goes Here
- Aiken smart contract source code (.ak files)
- Contract deployment scripts
- NFT metadata templates (JSON structures)
- Minting policy definitions
- Character rarity algorithms
- Blockchain interaction scripts
- IPFS upload configurations
- Contract testing suites
- Audit reports and security docs

## Folder Structure Inside
```
6 nft contracts\
├── contracts\
│   ├── character_nft.ak      (Main NFT minting contract)
│   ├── marketplace.ak        (Trading functionality)
│   └── evolution.ak          (Character progression)
├── metadata\
│   ├── templates\            (JSON templates for each rarity)
│   └── generated\            (Actual metadata files)
├── scripts\
│   ├── deploy\               (Deployment to Cardano)
│   ├── mint\                 (Minting functions)
│   └── interact\             (Contract interactions)
├── tests\                    (Unit and integration tests)
└── docs\                     (Technical documentation)
```

## Use Cases
- Smart contract development and testing
- NFT minting infrastructure
- Blockchain integration with game
- Character ownership verification
- Marketplace functionality
- Rarity distribution management
- On-chain evolution mechanics

## NFT Metadata Template (CIP-68)
```json
{
  "721": {
    "policy_id": {
      "name": "Moses",
      "image": "ipfs://QmXxx...",
      "mediaType": "image/png",
      "rarity": "Covenant Bearer",
      "attributes": {
        "tier": "Legendary",
        "testament": "Old",
        "firstMention": "Exodus 2:10",
        "abilities": ["Part the Sea", "Ten Plagues", "Divine Law"],
        "stats": {
          "faith": 95,
          "wisdom": 90,
          "courage": 88,
          "humility": 75,
          "love": 82
        },
        "relationships": {
          "brother": "Aaron",
          "sister": "Miriam",
          "mentor": "Jethro"
        }
      }
    }
  }
}
```

## Rarity Distribution Algorithm
```
Divine Tier:        0.001% (3 unique)
Archangel Tier:     0.01%  (15 total)
Covenant Bearers:   0.1%   (25 total)
Major Prophets:     0.5%   (18 total)
Apostles:           1%     (16 total)
Matriarchs:         2%     (12 total)
Judges/Leaders:     3%     (20 total)
Faithful Servants:  5%     (40 total)
Gentile Converts:   8%     (8 total)
Common People:      15%    (300+ total)
```

## Smart Contract Functions

### Core Functions
- `mint_character()` - Create new NFT
- `evolve_character()` - Update based on story progress
- `trade_character()` - Marketplace functionality
- `verify_ownership()` - Check wallet ownership
- `get_character_data()` - Retrieve metadata

### Evolution Mechanics
Characters can evolve through story:
- Saul → Paul (transformation)
- David (shepherd) → David (king)
- Moses (prince) → Moses (prophet)

### Soulbound Rules
Divine tier (Jesus forms) cannot be traded

## Development Checklist
- [ ] Install Aiken CLI
- [ ] Set up Cardano testnet wallet
- [ ] Write character minting policy
- [ ] Create metadata generation script
- [ ] Test on Preview testnet
- [ ] Implement IPFS upload
- [ ] Build minting website
- [ ] Security audit
- [ ] Deploy to mainnet

## Useful Commands
```bash
# Install Aiken
cargo install aiken

# Build contract
aiken build

# Run tests
aiken check

# Generate metadata
node scripts/generate_metadata.js
```