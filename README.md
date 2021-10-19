ISO 3166-1 Landenlijst
=======================

## Installeren via NuGet

Als je ISO3166NL wil gebruiken in je project dan kan je [het direct installeren via NuGet](https://www.nuget.org/packages/)

Om ISO3166NL te installeren, voer je het volgende commando uit in de "Package Manager Console"

```
PM> Install-Package ISO3166NL
```

## Gebruik

```
Country[] countries = ISO3166NL.Country.List;
```

## Country Model

```
public string Name { get; private set; }
public string TwoLetterCode { get; private set; }
public string ThreeLetterCode { get; private set; }
public string NumericCode { get; private set; }

public static readonly Country[] List = new[] {...};
```

Laatste controle met de officiële ISO 3166 (https://www.iso.org/obp/ui/#search) op 18 oktober 2021.

License: MIT
