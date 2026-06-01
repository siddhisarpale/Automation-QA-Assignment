Task 2 – n8n API Integration Workflow

API Used:
1. CoinGecko API

Purpose:
The workflow retrieves cryptocurrency market data from CoinGecko.

Transformation:
The response data is filtered to keep only the top cryptocurrencies by market capitalization.

Enrichment:
A second API request fetches detailed information about Bitcoin, including market data and pricing information.

Trigger:
Manual Trigger (used for testing).

Error Handling:
Workflow was tested with successful API responses. Additional error handling can be extended using n8n error branches and continue-on-fail options.

Output:
Structured JSON output generated successfully inside n8n.