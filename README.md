Keycomb Simple Example
=====

To run a simple test of Keycomb picking up an accidental key commit, do the the following: 

1) Fork https://github.com/keycomb/keycomb-simple-example

2) Sign-in at https://keycomb.io, refresh your repo list and activate Keycomb on your repo `keycomb-simple-example`

3) Locally, run:
```shell
$ git clone https://github.com/<your-username>/keycomb-simple-example.git
$ cd keycomb-simple-example
$ git checkout -b config-updates
$ echo '  key: AKIA1234567890123456' >> config.yaml
$ git commit -a -m "update config" 
$ git push origin config-updates
```

4) Return to https://github.com and create a PR from the pushed branch `config-updates`. (Be sure to create a PR to your own master branch and not the forked repo.)

5) In the PR's "checks" section, watch Keycomb run!