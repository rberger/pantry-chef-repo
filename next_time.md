In the future, you can modify the Policyfile.rb, then run
`chef update` and `chef export zero-repo`, then rerun chef client with
`sudo /opt/chefdk/embedded/bin/chef-client -z` from this directory.
