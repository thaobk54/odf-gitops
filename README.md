# ODF GitOps (Release-4.19)
Deploy từ custom images trên quay.io/thaobk541.
Test trước: oc apply -k base/ && oc get csv -n openshift-storage (chờ Succeeded).
Sau đó: oc apply -k odf-resources/.
