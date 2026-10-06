# HASHCALL — Public Proof #0001

**Every Call. Unerased.**

**Status:** COMMITMENT PUBLISHED · BITCOIN TIMESTAMP VERIFIED

HASHCALL committed to a specific state of its `DMA_v0.1` signals ledger before the first formal review.

## Commitment

- **Capture time — self-reported:** `2026-10-05T17:55:24.437570Z`
- **Signals committed:** `432`
- **Committed bytes:** `693811`
- **Ledger prefix SHA256:**  
  `aa0099c1ad6402f4a92e5b9508469ba6d6417a6c96bd31463ae506fe376466ef`

## Canonical commitment record

The canonical commitment record is exactly **167 bytes**, ASCII / UTF-8 compatible, with **no trailing newline**:

```text
HASHCALL PUBLIC PROOF v0.1 | DMA_v0.1 | 2026-10-05T17:55:24.437570Z | rows=432 | bytes=693811 | sha256=aa0099c1ad6402f4a92e5b9508469ba6d6417a6c96bd31463ae506fe376466ef
```

**Record SHA256**

`a3989a3b76ae78c0247ae443e0ec77a9b2ada7fa06512de7f429aff0ca4ef47f`

This exact record is the object submitted to OpenTimestamps.

## What this proves

This commitment identifies the exact first **693,811 bytes** of the HASHCALL signals ledger as captured at the self-reported time above.

Once those same bytes are disclosed, anyone can independently calculate SHA256 and compare the result with the published ledger-prefix hash.

A match will show that the disclosed prefix is byte-for-byte identical to the data committed to by this record.

## What this does not prove

This commitment is **not a performance claim**.

It does not prove profitability, predictive accuracy, benchmark superiority, or any future review outcome.

It does not, by itself, prove that signals recorded before this commitment were logged at their stated times, or that none were removed before the commitment was made.

It does not prove that future signals cannot be changed or deleted.

It proves only the integrity of the specific ledger prefix identified above from the commitment point forward.

## Independent timestamp

The canonical 167-byte commitment record was submitted to OpenTimestamps, and the proof has since been upgraded with Bitcoin attestations.

### Original proof

- **Size:** `724 bytes`
- **SHA256:**  
  `70e671b15a2c65b65f7a0116bf6c91fae0025d0fd77e42a35cdd799dc73e7cde`

### Upgraded proof

- **Status:** `BITCOIN TIMESTAMP VERIFIED`
- **Size:** `3695 bytes`
- **SHA256:**  
  `a03c0de6456401d6076d9a157e834bad41f89322e3323ba7b9edec5bdc80d004`

Bitcoin attestations are present in the upgraded proof.
## Public disclosure

The exact committed **693,811-byte ledger prefix** will be published **no later than 27 October 2026**.

After disclosure, verification requires no proprietary HASHCALL software:

1. obtain the disclosed ledger prefix;
2. confirm its size is exactly `693811` bytes;
3. calculate SHA256;
4. compare the result with:

`aa0099c1ad6402f4a92e5b9508469ba6d6417a6c96bd31463ae506fe376466ef`

## Commitment chain

This is the genesis public-proof record.

- **Commitment ID:** `HASHCALL-PUBLIC-PROOF-0001`
- **Previous commitment record SHA256:** `GENESIS — NONE`

Future public commitments will include the SHA256 of the preceding canonical commitment record.

---

**We publish the outcome — whatever it is.**

**The call comes first. The facts come after.**
