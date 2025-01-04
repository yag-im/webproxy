# API Proxy

Routing and authentication service

## Local setup

API Proxy (:8080)           /            webapp devcontainer (:8086)
                            /api         yagsvc devcontainer (:8082) 
                            /webrtc      sigsvc devcontainer (:8081)
                            /auth        authsvc devcontainer (:?)

Other devcontainers (for reference):

sessionsvc (:8084)
appsvc (:8085)
jukeboxsvc (:8083)

Usage:

    make build
    make run
