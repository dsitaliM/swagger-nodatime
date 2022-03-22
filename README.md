# Swagger NodaTime
Simple package that deserializes NodaTime for ASP.NET 6 consumption


## Usage

```
var jsonSettings = new JsonSerializerOptions();
jsonSettings.AddNodaTime(DateTimeZoneProviders.Tzdb);

builder.Services.AddSwaggerGen(x => x.ConfigureForNodaTime(jsonSettings));

```
