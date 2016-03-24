---
title: "`srcset` 変更時に画像が更新されない場合があります"
date: "2016-03-24T15:26:00-04:00"
categories: ["dom"]
tags: []
versions: ["45"]
statuses: "regressed"
references:
    - url: "https://bugzilla.mozilla.org/show_bug.cgi?id=1259482"
      title: "Bug 1259482 - Product image not changing upon selection in Woocommerce/Wordpress"
---
Firefox 38 で導入された [`srcset`](https://developer.mozilla.org/ja/docs/Web/HTML/Element/img#attr-srcset) 属性を持つ [レスポンシブ画像](https://developer.mozilla.org/ja/Learn/HTML/Multimedia_and_embedding/Responsive_images) が、その属性値が特定の方法で動的に変更された際、正しく更新されないというリグレッションが Firefox 45 で発生しました。このバグは *WooCommerce* を使用したオンラインストア上の製品画像表示に影響しています。Mozilla 開発者が解決策に取り組みます。