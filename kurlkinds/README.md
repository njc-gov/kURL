To make a change to the Installer type.

1. Edit ./pkg/apis/cluster/v1beta1/installer_types.go
1. Run `make generate`
1. Make a PR and merge.
1. cd to ../kurl_util
1. Run `go get github.com/replicatedhq/kurl/kurlkinds`
1. Define a new bash variable in kurl_util/cmd/yamltobash/main.go to hold the value of the new field.
1. Use the new bash variable in kurl install scripts.
