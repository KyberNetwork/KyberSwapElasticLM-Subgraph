# Subgraph for Elastic LM 
Extract data from Elastic Liquidity Mining contract


# Deploy subgraph 

1. Build subgraph

Because we will track the contract on multiple chains, re-run build command will update the `subgraph.yaml` file for correct network

```
yarn build --network avalanche/arbitrum/optimism...
```

**Note**: need to check and update `networks.json` file for the correct data before running the command

2. Deploy subgraph

 
