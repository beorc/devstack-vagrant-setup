# devstack-vagrant-setup

Execute `vagrant up` to deploy locally OpenStack cloud.
Open http://192.168.1.201 in your browser to see the Horizon admin panel.

On error "Could not find suitable distribution for Requirement.parse('pbr>=2.0.0')" do:

	$ vagrant ssh
	$ /opt/stack/tempest/.tox/tempest/bin/pip install pbr

