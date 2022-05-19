## Sample repo to install the OCS/ODF, Red Hat 3Scale Api Management and Red Hat Single Sign-On on Openshift 4


### How to run
```console
  export TOKEN=<REPLACE_WITH_API_TOKEN>
  export API_SERVER_URL=<REPLACE_WITH_API_SERVER_URL>
  export STORAGE_SIZE_OCS=<500Gi>/<0.5Ti>/<2Ti>
  export STORAGE_CLASS_NAME=<gp2>
  ansible-playbook -e token=$TOKEN -e server=$API_SERVER_URL storage_size=$STORAGE_SIZE_OCS -e storage_class=$STORAGE_CLASS_NAME playbook.yaml
```
