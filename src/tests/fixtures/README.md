# Notes

## SSH Keys

libscrapli_test_ssh_key_with_passphrase has a passphrase of `libscrapli`

## SSH Certificates

libscrapli_test_ssh_key-cert.pub is an openssh user certificate for libscrapli_test_ssh_key (with
principals `admin` and `admin-sshkey`), signed by a throwaway CA whose private key was discarded.
The test devices do not trust that CA, so authenticating with this certificate is expected to
fail -- it is used to test certificate authentication failures.
