# apihub-simulacion-client-java [![GitHub Packages](https://img.shields.io/badge/Maven&nbsp;package-Last&nbsp;version-lemon)](https://github.com/orgs/APIHub-CdC/packages?repo_name=apihub-simulacion-client-java) 


Proyecto con el cual puedes invocar la simulación de los siguientes APIs:

* **Reporte de Cédito Consolidado con FICO® Score y Prevención de Lavado de Dinero** - *RCC-FS-PLD* - [ver aquí](https://github.com/APIHub-CdC/rcc-ficoscore-pld-client-java)
* **Reporte de Cédito Consolidado** - *RCC* - [ver aquí](https://github.com/APIHub-CdC/rcc-client-java)
* **FICO® Score** - *FS* - [ver aquí](https://github.com/APIHub-CdC/ficoscore-client-java)


* **Reporte de Cédito Consolidado con FICO® Score y Prevención de Lavado de Dinero** - *RCC-FS-PLD* - [ver aquí](https://github.com/APIHub-CdC/rcc-ficoscore-pld-simulacion-client-java)
* **Reporte de Cédito Consolidado con FICO® Score** - *RCC-FS* - [ver aquí](https://github.com/APIHub-CdC/rcc-ficoscore-simulacion-client-java)
* **Reporte de Cédito Consolidado** - *RCC* - [ver aquí](https://github.com/APIHub-CdC/rcc-simulacion-client-java)
* **Reporte de Cédito para Persona Moral** - *RCCPM* - [ver aquí](https://github.com/APIHub-CdC/rcc-pm-simulacion-client-java)
* **Reporte de Cédito** - *RC* - [ver aquí](https://github.com/APIHub-CdC/rc-simulacion-client-java)
* **FICO® Score** - *FS* - [ver aquí](https://github.com/APIHub-CdC/ficoscore-simulacion-client-java)



## Requisitos

1. Java >= 1.7
2. Maven >= 3.3

## Instalación

**Prerrequisito**: obtener token de acceso y configuración de las credenciales de acceso. Consulte el manual **[aquí](https://github.com/APIHub-CdC/maven-github-packages)**.

**Opción 1**: En caso que la configuración se integró en el archivo **settingsAPIHUB.xml** (ubicado en la raíz del proyecto), instale las dependencias con siguiente comando:

```shell
mvn --settings settingsAPIHUB.xml clean install -Dmaven.test.skip=true
```

**Opción 2**: Si se integró la configuración en el **settings.xml** del **.m2**, instale las dependencias con siguiente comando:

```shell
mvn install -Dmaven.test.skip=true
```

## Guía de inicio

### Paso 1. Agregar el producto a la aplicación

Al iniciar sesión seguir los siguientes pasos:

 1. Dar clic en la sección "**Mis aplicaciones**".
 2. Seleccionar la aplicación.
 3. Ir a la pestaña de "**Editar '@tuApp**' ".
    <p align="center">
      <img src="https://github.com/APIHub-CdC/imagenes-cdc/blob/master/edit_applications.jpg" width="900">
    </p>
 4. Al abrirse la ventana emergente, seleccionar el producto.
 5. Dar clic en el botón "**Guardar App**":
    <p align="center">
      <img src="https://github.com/APIHub-CdC/imagenes-cdc/blob/master/selected_product.jpg" width="400">
    </p>

### Paso 2. Preparar peticiones
Los proyectos de simulación se encuentran en clases test diferentes, cada uno es agregado como dependencia en el **pom.xml**. Las instrucciones para armar cada petición se encuentran en:

* **Reporte de Cédito Consolidado con FICO® Score y Prevención de Lavado de Dinero** - [ver aquí](https://github.com/APIHub-CdC/rcc-ficoscore-pld-simulacion-client-java)
* **Reporte de Cédito Consolidado con FICO® Score** - [ver aquí](https://github.com/APIHub-CdC/rcc-ficoscore-simulacion-client-java)
* **Reporte de Cédito Consolidado** - [ver aquí](https://github.com/APIHub-CdC/rcc-simulacion-client-java)
* **Reporte de Cédito para Persona Moral** - [ver aquí](https://github.com/APIHub-CdC/rcc-pm-simulacion-client-java)
* **Reporte de Cédito** - [ver aquí](https://github.com/APIHub-CdC/rc-simulacion-client-java)
* **FICO® Score** - [ver aquí](https://github.com/APIHub-CdC/ficoscore-simulacion-client-java)

### Paso 6. Ejecutar la prueba unitaria

Teniendo los pasos anteriores ya solo falta ejecutar la prueba unitaria, con el siguiente comando:
```shell
mvn test -Dmaven.install.skip=true
```

---
[CONDICIONES DE USO, REPRODUCCIÓN Y DISTRIBUCIÓN](https://github.com/APIHub-CdC/licencias-cdc)
