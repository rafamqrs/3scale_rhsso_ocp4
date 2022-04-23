## Sample repo to install the OCS/ODF, Red Hat 3Scale Api Management and Red Hat Single Sign-On on Openshift 4


### How to run
```console
  export TOKEN=<REPLACE_WITH_API_TOKEN>
  export API_SERVER_URL=<REPLACE_WITH_API_SERVER_URL>
  ansible-playbook -e token=$TOKEN -e server=$API_SERVER_URL playbook.yaml
```
