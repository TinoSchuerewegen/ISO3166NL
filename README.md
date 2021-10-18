# Install via Nuget
If you want to include ISO3166 in your project, you can install it directly from NuGet

To install ISO3166, run the following command in the Package Manager Console

  PM> Install-Package ISO3166

# Gebruik

  Country[] countries = ISO3166.Country.List;

# Country Model

  public string Name { get; private set; }
  public string TwoLetterCode { get; private set; }
  public string ThreeLetterCode { get; private set; }
  public string NumericCode { get; private set; }

  public static readonly Country[] List = new[] {...};

Laatste controle met de officiële ISO 3166 (https://www.iso.org/obp/ui/#search) op 18 oktober 2021.

License: MIT
