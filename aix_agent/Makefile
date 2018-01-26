aix_agent_exec : aix_agent.go utils.go
	mkdir -p build
	gccgo *.go -g -o build/$@

clean :
	rm -rf build
