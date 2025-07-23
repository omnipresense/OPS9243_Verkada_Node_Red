# OPS9243_Verkada_Node_Red
Node Red node configuration for configuring OPS9243-A speed message for passing into Verkada Command dashboard

Nodes provided are available to import into a Node Red dashboard.  The nodes receive the MQTT speed messages from the OPS9243-A, check the format and payload, reformat the message with proper IDs/tokens, and pass via HTTP POST to Verkada Command dashboard.  See AN-28, Enabling Verkada LPR Camera with Radar Speed Reports, for complete description of creating a Helix Event and generating the proper ID/tokens which are input into the proper nodes.  Search JSON text for nodes with <insert...> to configure with the proper IDs/tokens.
