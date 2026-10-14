# RWAI Airdrop Landing Page

Design reference for the RWAI airdrop landing page.

> Static design preview. Rebuild in your own stack using this as the visual and behavioral reference. Not for direct production use.

## Structure

- `index.html` - Landing page (single file, CSS/JS inline)
- `img*` - Image assets (webp/jpg/png/svg)

## Sections

1. Hero - "Apply daily. Own what's next."
2. Token intro - "Meet the token behind this airdrop."
3. Clients - Logo grid
4. Investors - Coming soon (logos hidden)
5. How it works - 5 steps
6. Q&A
7. Entry CTA - "Ready for your next airdrop entry?"

## Entry Flow (demo)

1. **Buy Now** - Goes to login screen (login required)
2. After login - **Review entry transaction** modal opens
3. Select **Base** or **BSC**
4. **Confirm in wallet** - Modal closes, CTA shows "Already applied today."

No real wallet or on-chain transaction. Demo only.

## Specs

- Daily limit: "One entry per day per account"
- Gas: Base `0.0002 ETH` / BSC `0.0006 BNB`
- No entry price, gas only
- Font: Inter
- Light mode only
- Mobile 390px verified
