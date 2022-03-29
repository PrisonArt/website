# The Prison Art Project

People accrue debt while incarcerated. On returning to society, they struggle to find employment. An increasingly privatized system then reincarcerates these human beings for failure to pay their debts. It is _exactly_ this kind of economic double-bind which open and permissionless networks for the creation and distribution of value can solve.

## Mission

To restore justice by interrupting the re-incarceration cycle of those unable to meet their debts.

To cultivate dignity and respect for life.

## Our Motivation

Justice involved people incur financial obligations as a result of their history and incarceration, like restitution payments for victims, court fees, and driver's license reinstatement fees. Upon release, 88% of states re-incarcerate people for failure to pay back these debts, accounting for roughly 30% of recidivism in the US.

## Our Solution

The PR1S0N Art project teams up with existing justice-involved artist programs to create digital collections. Each collection is sold as an NFT on Ethereum. The funds raised from the sale are used to pay prisoner’s financial debts, reducing re-entry friction, re-incarceration rates, restoring dignity to the returning citizens and enabling government institutions to retrieve billions of dollars in uncollected debts.

Receipts from debt payments are added back to the collection, so a collector holds not just art, but the full transactional story of a human being's restorative journey. The collection may include artworks from multiple artists, but is sold as a single object, which creates a provably equitable way of splitting funds among artists.


## Architecture

```
          ,-.                  ,-.
          `-'                  `-'
          /|\                  /|\
           |                    |                         ,---------.              ,---------.
          / \                  / \                        | Restore |              | Justice |
         Buyer               pr1s0n art                   `----+----'              `----+----'
           |                    |        mints new NFT        |                         |     
           |                    |---------------------------->|                         |     
           |                    |                             |                         |     
           |                    |                             |                         |     
           |                    |        sets up auction      |                         |     
           |                    |------------------------------------------------------>|     
           |                    |                             |                         |     
           |    makes bid       |                             |                         |     
           |--------------------------------------------------------------------------->|     
           |                    |                             |                         |     
           |                    |                             | winning bid freezes NFT |     
           |                    |                             |<------------------------|     
           |                    |___________________          |   funds to PA payment   |     
        ________                |      |<-----------|---------|-------------------------|     
       |   |    |  exchange + pay LFOs |            |         |      10% to PA Fund     |     
       |   |    |<---------------------|            |<--------|-------------------------|     
       |   |    |               |      |            |         |                         |     
    Artist |  State             |  pr1s0n art       |         |                         |     
           |                    |   payment         |         |                         |     
     ,-.   |                    |     ,-.           |         |                         |     
     `-'   |                    |     `-'  reattach |         |                         |     
     /|\   |                    |-----/|\-----------|-------->|                         |     
      |    |                           |   receipt  |         |                         |     
     / \   |                          / \           |         |                         |     
           |                                        |         |                         |     
           |           safeTransfer to buyer        |         |                         |     
           |<-------------------------------------------------|                         |     
           |                                       ,-.        |                         |     
           |                                       `-'        |                         |     
           |                                       /|\        |                         |     
           |                                        |         |                         |     
           |                                       / \        |                         |     
           |                                    pr1s0n art    |                         |     
           |                                       fund       |                         |         
```

## Is This A DAO?

The DAO that can be named is not the eternal DAO.

Open, verifiable, executable contracts on ownerless networks allow us to organise institutions which are more like shared practices and customs than complex bureaucracies. We offer here a description of a **shared practice** for systems of restorative justice.