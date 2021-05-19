## Odoo Argentina - Módulos indispensables
Los módulos aquí incorporados no son mantenidos por Geneos. La cooperativa sólo los utiliza.

# Odoo conf
Agregar las siguientes lineas en su archivo de configuracion, en la sección *addons*:
> <path_to_modules>/odoo-argentina/odoo-argentina-ce, <path_to_modules>/odoo-argentina/odoo-argentina-ee, <path_to_modules>/odoo-argentina/odoo-argentina, <path_to_modules>/odoo-argentina/account-payment, <path_to_modules>/odoo-argentina/account-financial-tools, <path_to_modules>/odoo-argentina/web

**NOTA:** reemplazar *<path_to_modules>* por la ruta donde usted colocó su repositorio

# ¿Cómo clonar este repositorio?
> git clone -b 13.0 --recurse-submodules https://github.com/coopgeneos/odoo-argentina.git

# ¿Cómo actualizar los módulos?
> git submodule update --remote
