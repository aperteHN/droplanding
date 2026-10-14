# RWAI Airdrop Landing Page

Design reference implementation for the RWAI airdrop landing page.

**Live preview:** https://rwai-drop-b221b230.vercel.app

> Design reference implementation - not for direct production use.
> This is a static design preview. Rebuild in your own stack using this as the visual and behavioral reference.

## Files

- `index.html` - Main landing page (single file, all CSS/JS inline)
- `img*.webp` / `img*.jpg` / `img*.png` / `img*.svg` - Image assets referenced by index.html

## Page Flow

1. **Hero** - "Apply daily. Own what's next." with Buy Now / How it works
2. **Token intro** - "Meet the token behind this airdrop."
3. **Clients** - Client logo grid
4. **Investors** - Logo marquee
5. **How it works** - 5 steps: Login → Connect wallet → Select network → Confirm entry → Check in My Page
6. **Q&A** - Airdrop FAQ
7. **Purchase CTA** - "Ready for your next airdrop entry?" with Buy Now

## Purchase Flow (demo)

1. Click **Buy Now** (bottom section) → transitions to login screen
2. After login → **Review entry transaction** modal opens
3. Select **Base** or **BSC** network tab
4. Click **Confirm in wallet** → modal closes, CTA becomes disabled with "Already applied today."

Note: No real wallet connection or on-chain transaction. Demo simulation only.

## Key Copy

- Daily limit: "One entry per day per account"
- Gas fees: Base `0.0002 ETH` / BSC `0.0006 BNB`
- No entry price, gas fee only

## Design Notes

- Font: Inter (Latin) / Noto Sans KR (Korean)
- Light mode only
- Mobile: 390px verified, no horizontal overflow
- Modal: compact on mobile with internal scroll
