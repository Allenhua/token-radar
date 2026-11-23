# token-radar

A token launch radar for the make.fun token-radar-01 bounty. It reads the sealed
DefiLlama snapshot, ranks protocols that record no token by an implied token value
calibrated from the snapshot's own live-token protocols (median market-cap-to-TVL
per category, winsorized and shrunk toward the global median), and writes a static
dashboard with a farm plan for every protocol.

Run: `MAKEFUN_OUTPUT_DIR=out node main.ts --input <snapshot.json>`
