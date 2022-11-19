# A Docker Experiment

I'm recording here the Docker container setup I'll create on my home server.

At the least I'll want the following containers:
1. Plex Server
2. Download area (check validity/safety)
3. Personal, secure data storage
4. DNS/PiHole (maybe 2 separate containers?)
5. Sandbox

## Plex Server

Self-explanatory. A container for my Plex server, with access to the relevant files.

## Download Playground

For DLing anything I want without chances of infection/corruption.

## Data storage

Docker containers don't really do storage, so maybe get a couple SSDs, add as separate pool, and encrypt. Use the container as a SMB/NFS share to access those files.

## DNS/PiHole

PiHole for more malicious ads, DNS for easier access to containers.

## Sandbox

For playing.

