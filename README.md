# Google's glog with default flags change 

so that it works better with Kubernetes

Changes includes: 

1. logtostderr=true so that glog won't write to files any more (thus faster execution)
2. Shorter log prefix: pid removed

