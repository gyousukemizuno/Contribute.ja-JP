---
title: ms-prod-missing
description: Docs のビルドの問題 ms-prod-missing に関する説明と解決方法
author: meganbradley
ms.author: mbradley
ms.topic: error-reference
ms.date: 2/2/2019
ms.prod: non-product-specific
ms.openlocfilehash: 9b3f209ca2300735210490ffd58c3ac423c44fef
ms.sourcegitcommit: 8e897e90268a8a87dc4b97d7c28d22ed5950c8d9
ms.translationtype: HT
ms.contentlocale: ja-JP
ms.lasthandoff: 03/29/2019
ms.locfileid: "58636772"
---
# <a name="ms-prod-missing"></a>ms-prod-missing

[!INCLUDE [suggestion-note](includes/suggestion-note.md)]

## <a name="suggestion"></a>提案

`Missing attribute: ms.prod. If you specify ms.technology, you must also specify ms.prod.`

オンプレミスの製品を指定する場合は `ms.prod` を使います。 `ms.prod` に関する詳細情報を指定する場合は、必要に応じて `ms.technology` を指定できます。ただし、`ms.technology` を指定する場合は、`ms.prod` も指定する必要があります。 `ms.prod` と `ms.technology` に対する値は有効なペアである必要があります。

## <a name="resolution"></a>解決方法

指定した `ms.technology` の値がご自分の記事に対して適切かどうか確認します。 次に、`ms.technology` の有効な親となる、適切な `ms.prod` の値を追加します。

有効な値は、[こちらの Microsoft 内部サイト](https://docsmetadatatool.azurewebsites.net/allowlists)にあります。

<!--make sure to add this file to your includes folder and verify the path-->
[!INCLUDE [validation-reference-help](includes/validation-reference-help.md)]
