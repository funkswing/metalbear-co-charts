# mirrord Operator Helm Crate

To setup the mirrord Operator on your cluster you can use this Helm chart.
* You must add `license.key` or license file to `values.yaml` or create a secret with key `OPERATOR_LICENSE_KEY` with the key as value and set `keyRef`.
* If `certManager.enabled` is set to `false`, you must set `tls.data['tls.key']` and `tls.data['tls.crt']`
