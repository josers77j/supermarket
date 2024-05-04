<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

<p align="center">
<a href="https://github.com/laravel/framework/actions"><img src="https://github.com/laravel/framework/workflows/tests/badge.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>


## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
# supermarket


# COMANDOS
## Para ejecutar el proyecto puedes usar el siguiente comando (ten en cuenta que este comando funciona si tienes definido un alias):
- sail stop && sail up -d && npm run dev

## Comando para obtener la direccion ip de wsl para la red y asi utilizar un gestor de base de datos como tableplus o ddbeaver.
- wsl hostname -I

## ALIAS EN ZSH
- alias sail='./vendor/bin/sail'


## Asegúrate de que tengas una clave SSH pública y privada configurada en tu sistema. Por lo general, se encuentran en ~/.ssh/id_rsa (clave privada) y ~/.ssh/id_rsa.pub (clave pública).
## Inicia el agente SSH:
Abre una terminal y ejecuta el siguiente comando para iniciar el agente SSH:
- eval "$(ssh-agent -s)"
## Agrega tu clave privada al agente SSH:
Usa el siguiente comando para agregar tu clave privada al agente SSH:
- ssh-add ~/.ssh/id_rsa
## Configura tu archivo SSH config (opcional pero recomendado):
- Puedes configurar tu archivo ~/.ssh/config para especificar la clave SSH a usar para ciertos hosts.
- Abre o crea el archivo ~/.ssh/config y agrega la configuración para tu host de GitHub:
---
- Host github.com
-  IdentityFile ~/.ssh/id_rsa