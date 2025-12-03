<p align="center"><img src="https://raw.githubusercontent.com/titaniumnetwork-dev/-Static/main/public/uv.png" height="200"></p>

<h1 align="center">-App</h1>

> [!CAUTION]
> Please note that this project isn't really maintained anymore before making issues! It has been superseded by [](https://github.com/MercuryWorkshop/scramjet). An example application setup can be found [here](https://github.com/MercuryWorkshop/Scramjet-App).

The deployable all-in-one bundle for [](https://github.com/titaniumnetwork-dev/), a highly sophisticated proxy used for evading internet censorship or accessing websites in a controlled sandbox using the power of service-workers and more!

## Deployment

[![Deploy on Railway](https://binbashbanana.github.io/deploy-buttons/buttons/remade/railway.svg)]

If you are deploying to an alternative service or to a server, refer to [Deploy via terminal](https://github.com/titaniumnetwork-dev//wiki/Deploy-via-terminal).

Additional information such as [customizing your frontend](-App/wiki).

Support and updates can be found in our [Discord Server](discord.gg/unblock).

> [!IMPORTANT]  
> Until deployed on a domain with a valid SSL certificate, Firefox will not be able to load the site. Use chromium for testing on localhost

### HTTP Transport

The example uses [EpoxyTransport](https://github.com/MercuryWorkshop/EpoxyTransport) to fetch proxied data encrypted.

You may also want to use [CurlTransport](https://github.com/MercuryWorkshop/CurlTransport), a different way of fetching encrypted data, or [Bare-Client](https://github.com/MercuryWorkshop/Bare-as-module3), the legacy (unencrypted!) transport.

See the [bare-mux](https://github.com/MercuryWorkshop/bare-mux) documentation for more information.
