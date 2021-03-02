#### Get the gateway
`route -n get default | grep gateway | awk '{{print $2}}'`
#### Get the interface
`route -n get default | grep interface | awk '{{print $2}}'`
