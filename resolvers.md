# resolvers

To use that list, add this to the `[sources]` section of your
`dnscrypt-proxy.toml` configuration file:

    [sources.'resolvers']
    urls = ['https://source.extera.xyz/rustyraven/dnscrypt-resolvers/raw/branch/main/resolvers.md']
    cache_file = 'resolvers.md'

--


## rustyraven

DNS resolver with ALFIS and OpenNIC.

sdns://AwQAAAAAAAAACTIuMjYuMi45MQARZG5zLnJ1c3R5cmF2ZW4ucHc