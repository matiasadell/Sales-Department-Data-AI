# Departamento de Ventas | IA

### Introducción
- Para que las empresas se vuelvan competitivas y disparen su crecimiento, necesitan aprovechar la IA / ML para desarrollar modelos predictivos para pronosticar las ventas en el futuro.

- Los modelos predictivos intentan pronosticar las ventas futuras basandose en datos histdricos, al tiempo que tienen en cuenta los efectos de la estacionalidad, la demanda, las vacaciones, las promociones y la competencia.

- El objetivo es predecir las ventas diarias futuras en función de las caracteristicas, así facilitar al Departamento de Ventas.

![](https://media-exp1.licdn.com/dms/image/C4D05AQHp-Hn0b_eKjg/feedshare-thumbnail_720_1280/0/1667609977867?e=1670641200&v=beta&t=BQo9A8uNc7MM9mEB_XTbTSNgwNxMYFr-Vw4V8egMIac)

### Dataset
- **Id**: ID de transacción (combinación de la tienda y la fecha).

- **Store**: identificador Unico de la tienda.

- **Sales**: ventas diarias, esta es la variable objetivo.

- **Customers**: numero de clientes de un dia dado.

- **Open**: Booleano para indicar si la tienda estaba abierta o cerrada (0 = cerrada, 1 = abierta).

- **Promo**: describe si la tienda tenia algun tipo de promoción ese dia o no.

- **StateHoliday**: indica si el dia era festivo o no (a = vacaciones publicas, b = vacaciones de Pascua, c = Navidades, 0 = No era festivo).

- **SchoolHoliday**: indica si (Store, Date) se ve afectado por el cierre de las escuelas publicas.

- **StoreType**: categoria que indica el tipo de tienda (a, b, c, d).

- **Assortment**: a = basico, b = extra, c = extedido.

- **CompetitionDistance (en metros)**: distancia a la tienda de la competencia mas cercana.

- **CompetitionOpenSince [Mes/Año]**: fecha en que abrió la competencia.

- **Promo2**: es una promoción continuada y consecutiva en algunas tiendas (0 = la tienda no participa, 1 = la tienda participa).

- **Promo2Since [Año/Semana]**: fecha en la que la tienda empieza a participar en la Promo2.

- **Promointerval**: describe los intervalos consecutivos donde la Promo2 empieza, indicando los meses en los que empieza la misma. P.e. "Feb,May,Aug,Nov" significa que cada nueva ronda de promoción empieza en Febrero, Mayo, Agosto, Noviembre de cualquier año de esa tienda.
