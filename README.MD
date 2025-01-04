# Web Proxy

Web routing and authentication service.

## Local setup

Web Proxy (:8080)           /            webapp devcontainer (:8086)
                            /api,/auth   webapi devcontainer (:8082) 
                            /webrtc      sigsvc devcontainer (:8081)

Other devcontainers (for reference):

sessionsvc (:8084)
appsvc (:8085)
jukeboxsvc (:8083)

Usage:

    make build
    make run
