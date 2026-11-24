# IC Definition Schema

Please use [`hardware/ics/7400.json`](https://github.com/ivanhaievyi/breadboard/blob/main/hardware/ics/7400.json) as a template for consistency.

| Field | Type | Description |
| :--- | :--- | :--- |
| `partNumber` | `string` | Standard IC identifier (`"7400"`). |
| `families` | `string[]` | Supported logic families ("74LS", "74HC"]`). |
| `name` | `string` | Part description. |
| `package` | `object` | Physical metadata (`type`, `pinCount`, `pinoutOrder`). |
| `supply` | `object` | Power/ground pin numbers (`vccPin`, `gndPin`) and ratings. |
