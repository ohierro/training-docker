## Creando el manager

```bash
docker swarm init --advertise-addr <nuestra IP>

To add a worker to this swarm, run the following command:

    docker swarm join \
    --token SWMTKN-1-1j6yll9ltuh425bvtl1ryvy85p6eejb9b9emhrlyty9dheh3ci-b3vg081kudoe8qlae37kx9pm0 \
    <IP>:2377

To add a manager to this swarm, run 'docker swarm join-token manager' and follow the instructions.
```

Para comprobar

```bash
docker info

Swarm: active
 NodeID: pqkggxqy0qa4r84g0ne3ppv0z
 Is Manager: true
 ClusterID: 235x276hgw86tvq7ysl9rixo0
 Managers: 1
 Nodes: 2
```

