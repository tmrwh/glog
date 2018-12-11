# Google's glog with some improvements

so that it works better with Kubernetes

Changes includes: 

1. logtostderr=true so that glog won't write to files any more (thus faster execution)
2. Shorter log prefix: pid removed

