> 🥥 Preview Notes
>
> The April preview release introduces a new operation:
>
> - Get Output Metrics Info
>
> **⚠️ Warning:** All API operations listed above are in preview. Consumers should review and adapt to any changes when these operations or alternatives become publicly available, as they may not be backward compatible. Please contact your customer success manager for more details.

---

# Risk Data API

## Get Output Metrics Info

The Get Output Metrics Info operation returns available granularities (only geoId specific) of loss tables and stats for a given analysisId. Analyses of ELT framework are only supported.

```json
{
  "granularities": {
    "lossTables": [
      {
        "exposureResourceTypeID": 7962,
        "perspectiveCodes": ["RL", "GU", "GR"]
      }
    ],
    "stats": [
      {
        "exposureResourceTypeID": 7950,
        "perspectiveCodes": ["RL", "GU", "GR"]
      }
    ]
  }
}
```
Find more details on:
[exposureResourceTypeID](https://developer.rms.com/platform/docs/response-filtering#exposure-type-filters),
[perspectiveCodes](https://developer.rms.com/platform/docs/response-filtering#perspective-filters)
