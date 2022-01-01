<h1 align="center">Hi 👋, I'm Ramazan Günindi</h1>
<h3 align="center">The steps applied in this project are described below.</h3>
-----------------------------------------------------------------------------------------------------------

> Info: `Isac makes different payments from 16 different countries. `

```feature  
Feature: make a payment to three different client

  @payment
  Scenario Outline: make payment for each country in countries list
    When Catch older version pop_up And LoginApp
    Then Open payment page
    When client country is <Country> Country and <Amount> Amount and <Phone> Phone and <Name> Name
    Then client balance check <Amount> amount
    Then client logout successfully
    Examples:
      | Country     |  | Amount |  | Phone      |  | Name |
      | India       |  | 30     |  | 5557891501 |  | Isac |
      | USA         |  | 20     |  | 5557891501 |  | Isac |
      | ICELAND     |  | 40     |  | 5557891501 |  | Isac |
      | GREENLAND   |  | 80     |  | 5557891501 |  | Isac |
      | Switzerland |  | 90     |  | 5557891501 |  | Isac |
      | NORWAY      |  | 60     |  | 5557891501 |  | Isac |
      | NEW ZEALAND |  | 60     |  | 5557891501 |  | Isac |
      | GREECE      |  | 10     |  | 5557891501 |  | Isac |
      | ITALY       |  | 70     |  | 5557891501 |  | Isac |
      | IRELAND     |  | 30     |  | 5557891501 |  | Isac |
      | China       |  | 50     |  | 5557891501 |  | Isac |
      | JAPAN       |  | 20     |  | 5557891501 |  | Isac |
      | FRANCE      |  | 60     |  | 5557891501 |  | Isac |
      | Russia      |  | 70     |  | 5557891501 |  | Isac |
      | Australlia  |  | 80     |  | 5557891501 |  | Isac |
      | CANADA      |  | 90     |  | 5557891501 |  | Isac |
```    

