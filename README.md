# ARSB-Product-Card

este es un paquete de prueba de despliegue NPM

### Arnoldo Suárez Bonilla - NI

## Ejemplo

```
import {ProductCard, ProductImage, ProductTitle, ProductButtons} from 'arsubo-shopping-cart'
```

```
const product = {
  id: "1",
  title: "Coffee Mug - Card",
  img: "./coffee-mug.png",
};

<ProductCard
product={product1}
initialValues={{
          count: 4,
          maxCount: 10,
        }} >
{({ count, reset, isMaxCountReached, increaseBy, maxCount }) => (
<>
<ProductImage />
<ProductTitle />
<ProductButtons />
</>
)}
</ProductCard>
```
