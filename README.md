# New project to test our operator
oc new-project memcached

# Create the operator scaffold
operator-sdk new memcached-operator --type=ansible --api-version=cache.cvicens.com/v1alpha1 --kind=Memcached --skip-git-init

> If you know you need a playbook: operator-sdk new memcached-operator --type=ansible --api-version=cache.cvicens.com/v1alpha1 --kind=Memcached --generate-playbook  --skip-git-init

