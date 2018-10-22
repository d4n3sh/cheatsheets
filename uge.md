##### Disable a node in UGE
```
qmod -d \<queue@nodename> -msg <"Message">
$ qmod -d \h*@node002 -msg "Taking offline for testing"
```

##### Enable a node in UGE
```
qmod -e \<queue@nodename> -msg <"Message">
$ qmod -e \*@testnode001 -msg "Ready for use"
```
