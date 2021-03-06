---
title: Data via apis guide
summary: Description of how to consume data via integrated apis.
authors:
    - Patrick Lamplmair
---

# Consume data via APIs guide

In this guide you will learn how you can consume your own datasets and subscriptions via the built in APIs of your DataSpace Node. This guide covers the following topics:

- [Prerequisites](/guides/guide-data-via-apis/#prerequisites)
- [Trust API](/guides/guide-data-via-apis/#trust-api)
- [Data API](/guides/guide-data-via-apis/#data-api)
- [Next step: verify a data stream](/guides/guide-data-via-apis/#next-step-verify-a-data-stream)

## Prerequisites

The prerequisits for consuming data from a subscription via the integrated APIs are the following:

- A granted subscription to a dataset (you are also able to visualize your own datasets)
- Data existists on owner side within the selected time-frame (Master DB)
- Data is allready synchronised on the consumer side (Slave DB)

## Trust API

The Trust API provides the interface to consume/store signed hashes of DataSpace Agents and/or to consume/store values by using the Trust API's built in Agent (the recommond way to integrate server-side data sources). Every method requires the **UUID** of a data stream.

Navigate to the Trust API via the "Tools" section of your DataSpace Node or you can follow this link to our demonstrator instance: <a href="https://trust-layer-api.tributech.dataspace.network/" target="_blank">Trust API</a>

## Data API

The Data API provides the interface to consume/store or consume values according to an **UUID** of an data stream.

Navigate to the Trust API via the "Tools" section of your DataSpace Node or you can follow this link to our demonstrator instance: <a href="https://data-api.tributech.dataspace.network/swagger" target="_blank">Data API</a>

## Next step: verify a data stream

In this guide, you have learned how to consume data via APIs of your DataSpace Node. To learn more about how you can verify a data stream, continue with the guide [Verify Data Stream](/guides/guide-verify-data-stream).
