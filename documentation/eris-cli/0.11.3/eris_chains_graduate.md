---

layout:     documentation
title:      "Documentation | eris:cli | eris chains graduate"

---

# eris chains graduate

Graduate a chain to a service.

## Synopsis

Graduate a chain to a service.

Graduate works by translating the chain's definition into a service definition
file with the chain_id set as the service name and everything set for you to
more simply turn the chain on or off.

Graduate should be used whenever you are "finished" working "on" the chain and
you feel the chain is stable. While chains work just fine by turning them "on"
or "off" with [eris chains start] and [eris chains stop], some feel that it is
easier to work with chains as a service rather than as a chain when they are
stable and not longer need to be worked "on" which is why this functionality
exists. Ultimately, graduate is a convenience function as there is little to
no difference in how chains and services "run", however the [eris chains]
functions have more convenience functions for working "on" chains themselves.

```bash
eris chains graduate NAME
```

## Options inherited from parent commands

```
  -d, --debug            debug level output
  -m, --machine string   machine name for docker-machine that is running VM (default "eris")
  -v, --verbose          verbose output
```

## See Also

* [eris chains](https://docs.erisindustries.com/documentation/eris-cli/0.11.3/eris_chains/)	 - Start, stop, and manage blockchains.

## Specifications

* [Actions Specification](https://docs.erisindustries.com/documentation/eris-cli/0.11.3/actions_specification/)
* [Chains Specification](https://docs.erisindustries.com/documentation/eris-cli/0.11.3/chains_specification/)
* [Contracts Specification](https://docs.erisindustries.com/documentation/eris-cli/0.11.3/contracts_specification/)
* [Motivation](https://docs.erisindustries.com/documentation/eris-cli/0.11.3/motivation/)
* [Services Specification](https://docs.erisindustries.com/documentation/eris-cli/0.11.3/services_specification/)

