---
author: sptramer
ms.author: sttramer
manager: carmonm
ms.date: 09/05/2018
ms.topic: include
ms.prod: azure
ms.technology: azure-cli
ms.openlocfilehash: 5df14f939efdd0550b49261c88c8dc6518ada459
ms.sourcegitcommit: 8b9e10b960150dc08f046ab840d6a5627410db29
ms.translationtype: HT
ms.contentlocale: nl-NL
ms.lasthandoff: 09/07/2018
ms.locfileid: "44059259"
---
De [Azure SDK voor Go](https://github.com/Azure/azure-sdk-for-go) is compatibel met Go-versie 1.8 en hoger. Voor omgevingen die gebruikmaken van [Azure Stack-profielen](/azure/azure-stack/user/azure-stack-version-profiles-go) is Go-versie 1.9 de minimale vereiste.
Volg [de installatie-instructies voor Go](https://golang.org/doc/install) als u Go moet installeren.

U downloadt de Azure SDK voor Go en de afhankelijkheden ervan via `go get`.

```bash
go get -u -d github.com/Azure/azure-sdk-for-go/...
```

> [!WARNING]
> Zorg ervoor dat u `Azure` in de URL in hoofdletters schrijft. Als u dit niet doet, kan dit importproblemen opleveren wanneer u aan het werk bent met de SDK. U moet `Azure` ook in uw importinstructies in hoofdletters schrijven.
