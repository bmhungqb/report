Install model analyzer
> pip3 install triton-model-analyzer
Run model analyzer
> model-analyzer <profile/report> --profile-models /workspace/model_respository --triton-launch-mode=<launch_mode> --output-model-repository-path /path/to/output -f <path to config file>
# profile: measure and record performance across various configurations
# report: generate comprehensive summary
# launch_mode: where is run triton inference server: docker, local, remote
	# remote -> add --triton-http-endpoint=<ip>:<port> 	
# model-analyzer -h to get more detail
