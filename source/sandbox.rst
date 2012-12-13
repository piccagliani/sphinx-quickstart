==========
Sandbox
==========

Sandboxです


===============
見出し(h1)
===============
h1 - h4まであります。

これはh2
========
ほげほげ

--------
これはh3
--------
ふがふが

これはh4
--------
もげもげ


インラインマークアップ
======================

**太字**

*斜体*

``リテラル``

`リンク付きテキスト <http://www.google.co.jp>`_

コードブロック
==============

::

 本ドキュメントはフィクションです。登場する人物、
 企業名は架空のものです。


.. code-block:: php

 <?php
 namespace sphinx;

 /**
  * Sample class.
  * @author gliani
  */
 class Sphinx
 {
     private $source = null;
     private $build = null;
 
     public function __construct($source, $build)
     {
         $this->source = $source;
         $this->build = $build;
     }
 
     public function make()
     {
     }
 }

.. code-block:: html

 <!DOCTYPE html>
 <html>
     <head>
         <meta charset="utf-8" />
         <title>HTML 5 complete</title>
         <!--[if IE]>
         <script src="http://html5shiv.googlecode.com/svn/trunk/html5.js"></script>
         <![endif]-->
     </head>
     <body>
         <p>Hello World</p>
     </body>
 </html>

リスト
======
リストたち

--------------
バレットリスト
--------------

* 東京都
* 神奈川
* 埼玉

--------------
数字付きリスト
--------------

1. ほげ
2. ふが
3. もげ
#. 餃子
#. ラーメン
#. チャーハン

--------------
定義リスト
--------------

餃子
   宇都宮の名物として有名。餃子の像もある。静岡の浜松がライバル。
ジャズ
   宇都宮はジャズの町としても売り出し中。
   楽器メーカーを多数抱える静岡の浜松がライバル
焼きそば
   知る人ぞ知る宇都宮の名物。専門店多数。なぜかビニール袋で持ち帰る。


ディレクティブ
==============

.. note::

 注釈です

.. warning::
 警告です

