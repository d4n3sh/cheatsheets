##### Disable a node in UGE
```
mmaddnode -N <nodename>
$ mmaddnode -N tesstnode001
```

##### Add gpfs client license
```
mmchlicense client --accept -N <nodename>
$ mmchlicense client --accept -N testnode001
```

##### Add gpfs server license
```
mmchlicense server --accept -N <servername>
$ mmchlicense server --accept -N testserver001
```
