# actions-lock-lab-action

A throwaway action for testing GitHub Actions workflow lockfiles (`actions.lock`). The `v1` tag is **force-pushed on purpose** during the experiments, so do not use it.

The action prints `OUTER_MARKER` and calls `./inner` through `OTA-EITA/actions-lock-lab-action/inner@v1`, which prints `INNER_MARKER`. Version A prints `A`, version B prints `B`.
