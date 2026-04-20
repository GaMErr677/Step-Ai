# Project TODO

- [x] Fix the Start Tracking button so pressing it does not make the screen disappear or reset unexpectedly
- [x] Add a proper motion permission flow without changing the current UI
- [x] Keep the existing app design and logic intact while improving step counting
- [x] Sync step count from device step data when available instead of relying only on live accelerometer input
- [x] Reduce false positive steps when the phone is stationary
- [x] Make the visible step count refresh on the intended 1-minute interval instead of updating immediately
- [x] Fix iPhone Safari browser step detection so real walking is counted again after the recent false-positive reduction changes
- [x] Recalibrate motion thresholds to a middle ground that still avoids counting while stationary
- [ ] Verify the visible step count still refreshes on the 1-minute timer while internal counting continues in real time

