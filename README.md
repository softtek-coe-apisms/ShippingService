ShippingService

Developed in ASP.NET Core.
The funcionality of the project is to return the total shipping cost.

Recives a total amount (double) as a parameter and the format of the request body is the following:
{
  "UserId": 0,
  "Productos": [
    {
      "ProductId": 0,
      "Quantity": 0
    }
  ]
}

The response body is similar to:
{
  "totalShippingCost": 440.00000000000006
}
__________________________

ShippingService
Desarrollado en ASP:NET Core
Recibe una cantidad total(double) como parámetro, y en el body se deben envíar también lo siguientes datos (en formato json):
{
  "UserId": 0,
  "Productos": [
    {
      "ProductId": 0,
      "Quantity": 0
    }
  ]
}


Regresa una respuesta tipo json con el total del costo de envío:
{
  "totalShippingCost": 440.00000000000006
}

