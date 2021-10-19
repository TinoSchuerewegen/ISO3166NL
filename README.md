ISO 3166-1 Landenlijst
=======================

## Installeren via NuGet

Als je ISO3166NL wil gebruiken in je project dan kan je [het direct installeren via NuGet](https://www.nuget.org/packages/ISO3166NL/)

Om ISO3166NL te installeren, voer je het volgende commando uit in de "Package Manager Console"

```
PM> Install-Package ISO3166NL
```

## Gebruik

```
Land[] landen = ISO3166NL.Land.List;
```

## Country Model

```
public string Naam { get; private set; }
public string TweeLetterCode { get; private set; }
public string DrieLetterCode { get; private set; }
public string NumeriekeCode { get; private set; }

public static readonly Land[] List = new[] {...};
```

Laatste controle met de officiële ISO 3166 (https://www.iso.org/obp/ui/#search) op 18 oktober 2021.

License: MIT
