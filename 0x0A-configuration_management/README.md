# create a file in /tmp

file { '/tmp/school':
	content => 'ILove Puppet',
	mode	=> '0744',
	owner	=> 'www-data',
	group	=> 'www-data',
}
