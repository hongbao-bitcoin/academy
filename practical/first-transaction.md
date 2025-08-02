# Sending Your First Transaction \ud83d\ude80

## Your First Step into the Bitcoin Network

Congratulations! You've received your hongbao and now you're ready to make your first Bitcoin transaction. This guide will walk you through sending Bitcoin safely and confidently.

## Before You Begin

### Prerequisites ✅
- [ ] Bitcoin in your wallet from hongbao
- [ ] Wallet app installed and secured
- [ ] Backup seed phrase stored safely
- [ ] Basic understanding of addresses

### Important Reminders ⚠️
- Bitcoin transactions are **irreversible**
- Always **double-check addresses**
- Start with **small amounts**
- **Network fees** are required

## Understanding Transaction Basics

### What Happens When You Send Bitcoin?

```
Your Wallet → Creates Transaction → Broadcasts to Network
                                           ↓
                                    Miners Validate
                                           ↓
                                    Added to Blockchain
                                           ↓
                                    Recipient Receives!
```

### Transaction Components

Every Bitcoin transaction includes:
1. **Input**: Where Bitcoin comes from (your address)
2. **Output**: Where Bitcoin goes (recipient's address)
3. **Amount**: How much to send
4. **Fee**: Payment to miners for processing

## Step-by-Step: Sending Bitcoin

### Step 1: Get Recipient's Address

The recipient needs to provide their Bitcoin address. They can:
- **Show QR code** (easiest)
- **Copy/paste address** (careful!)
- **Send via secure message**

#### Address Formats:
- **Legacy**: 1A1zP1eP5QGefi2DMPTfTL5SLmv7DivfNa
- **SegWit**: 3J98t1WpEZ73CNmQviecrnyiWrnqRhWNLy
- **Native SegWit**: bc1qar0srrr7xfkvy5l643lydnw9re59gtzzwf5mdq

All formats work - newer ones have lower fees!

### Step 2: Open Send Function

In your wallet:
1. Tap "Send" or paper airplane icon
2. Choose Bitcoin (not Lightning)
3. You'll see send screen

### Step 3: Enter Recipient Address

**Method 1: QR Code (Recommended)**
1. Tap QR scanner icon
2. Point at recipient's QR code
3. Address fills automatically
4. Verify it looks correct

**Method 2: Copy/Paste**
1. Copy address from recipient
2. Paste in address field
3. **Triple-check** every character
4. Look for validation checkmark

### Step 4: Enter Amount

You can enter amount in:
- **BTC**: 0.00012345
- **Satoshis**: 12,345
- **Your currency**: $50

Tips:
- Wallet shows your balance
- Can't send more than you have
- Leave some for fees!

### Step 5: Set Transaction Fee

Fees determine speed:

| Fee Level | Speed | Use Case |
|-----------|-------|----------|
| 🐌 Low | Hours/Days | Not urgent |
| 🚶 Medium | 30-60 min | Normal use |
| 🏃 High | 10-20 min | Time sensitive |
| 🚀 Priority | Next block | Urgent |

Most wallets suggest appropriate fees!

### Step 6: Review Everything

Before confirming, check:
- ✅ Correct recipient address
- ✅ Right amount
- ✅ Acceptable fee
- ✅ Total makes sense

### Step 7: Send!

1. Tap "Send" or "Confirm"
2. Enter PIN/biometrics if required
3. Transaction broadcasts to network
4. You'll see confirmation screen

### Step 8: Track Your Transaction

Your wallet shows:
- Transaction ID (long string)
- Status (pending → confirmed)
- Confirmations counter

You can also check on [mempool.space](https://mempool.space)

## Your First Practice Transaction

### Safe Practice Options

#### Option 1: Send to Yourself
1. Generate new receive address
2. Send small amount to it
3. Practice the process safely

#### Option 2: Lightning Wallet
1. Set up Lightning wallet
2. Send tiny amount
3. Near-instant and cheap

#### Option 3: Tip Someone
1. Find content creator accepting tips
2. Send small appreciation
3. Real transaction with purpose

## Understanding Confirmations

### What Are Confirmations?

Each new block added after your transaction = 1 confirmation

- **0 confirmations**: Pending (waiting for miners)
- **1 confirmation**: In blockchain (~10 minutes)
- **3 confirmations**: Very secure
- **6 confirmations**: Irreversible

### Why Wait for Confirmations?

- Small amounts: 1 confirmation usually fine
- Large amounts: Wait for 3-6
- Exchanges: Often require 3-6
- Personal choice based on trust

## Common Transaction Scenarios

### Sending to Friend
1. Meet in person or video call
2. They show QR code
3. You scan and send
4. Both see confirmation

### Paying for Goods/Services
1. Merchant provides address/invoice
2. Often includes exact amount
3. May have time limit
4. Save receipt/transaction ID

### Exchange Deposit
1. Generate deposit address on exchange
2. **Verify correct network** (Bitcoin, not others)
3. Send from wallet
4. Wait for exchange confirmations

### Testing New Wallet
1. Send minimum amount first
2. Verify it arrives
3. Test recovery if needed
4. Then send larger amounts

## Transaction Fees Explained

### What Determines Fees?

Fees based on:
- **Transaction size** (bytes, not Bitcoin amount)
- **Network congestion**
- **Desired speed**

NOT based on:
- Amount being sent
- Distance to recipient
- Wallet being used

### Fee Saving Tips
- Use Native SegWit addresses (bc1...)
- Send during low-congestion times
- Batch multiple payments together
- Consider Lightning for small amounts

## Troubleshooting Common Issues

### "Insufficient Balance"
- Check you have enough for amount + fee
- Wallet might be calculating conservatively
- Try reducing amount slightly

### "Invalid Address"
- Recheck every character
- Ensure it's a Bitcoin address
- Some wallets only accept certain formats

### "Transaction Stuck"
If fee too low:
- Wait - it may confirm eventually
- Use RBF (Replace-By-Fee) if available
- CPFP (Child-Pays-For-Parent) advanced option
- Learn for next time

### "Sent to Wrong Address"
- Cannot be reversed 😔
- Contact recipient if possible
- Expensive lesson learned
- Always double-check!

## Advanced Features

### Replace-By-Fee (RBF)
- Increase fee after sending
- Speeds up stuck transaction
- Not all wallets support

### Coin Control
- Choose specific UTXOs to spend
- Advanced privacy feature
- For experienced users

### Batch Transactions
- Send to multiple addresses
- Saves on fees
- Business use case

## Security During Transactions

### Always:
- ✅ Verify address character-by-character
- ✅ Start with test transaction
- ✅ Use secure internet connection
- ✅ Check wallet is authentic

### Never:
- ❌ Send to address from email
- ❌ Trust "refund" addresses
- ❌ Send under pressure
- ❌ Ignore warning messages

## After Your Transaction

### Save Records
- Transaction ID
- Recipient address  
- Amount and fee
- Purpose/notes

### Confirm Receipt
- Ask recipient to confirm
- Check blockchain explorer
- Wait for confirmations

### Learn and Improve
- What went well?
- What was confusing?
- How can you improve?

## Practice Challenges

### Beginner:
1. Send $1 to yourself
2. Try different fee levels
3. Watch confirmations

### Intermediate:
1. Send to friend and back
2. Use QR codes
3. Try RBF feature

### Advanced:
1. Use coin control
2. Create multi-output transaction
3. Experiment with Lightning

## Next Steps

<table data-view="cards"><thead><tr><th></th><th></th></tr></thead><tbody><tr><td>💰 <strong>Understanding Fees</strong></td><td><a href="understanding-fees.md">Deep dive into Bitcoin fees →</a></td></tr><tr><td>⚡ <strong>Lightning Network</strong></td><td><a href="lightning-network.md">Instant transactions →</a></td></tr><tr><td>🔒 <strong>Advanced Security</strong></td><td><a href="../security/private-keys.md">Protect your transactions →</a></td></tr></tbody></table>

---

> 🎉 **Congratulations!** You've made your first Bitcoin transaction! Each one gets easier. Remember: measure twice, cut once - or in Bitcoin: verify twice, send once!