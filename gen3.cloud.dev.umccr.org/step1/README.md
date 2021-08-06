# Step1 Config Mode

Step1 config contain minimal base services and Portal is in basic mode that just allow initial data submission for bootstrapping purpose.

You will need to use these config to override [`../manifest.json`](../manifest.json) and [`../portal/gitops.json`](../portal/gitops.json) while there is no data available in databases and/or no ES indexes. Typically, this is the situation: 
- A) the very first time setup or
- B) updating totally new data dictionary in `gen3 reset` with dropping all databases
