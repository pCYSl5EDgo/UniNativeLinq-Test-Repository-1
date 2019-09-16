# UniNativeLinq Test Repository 1

このリポジトリはUniNativeLinqのテストコード集その1です。
Unity Test RunnerのEditor Testを収載しています。
テストを実行しているUnityは2019.3です。

# なぜテストコードをPackageに同梱せず別リポジトリに分離しているのか？

UniNativeLinqDll.dllに全機能を入れると膨大になりエディタがフリーズするからです。
このリポジトリでは一部のAPIのみに絞ることでエディタがフリーズしない範囲でテストを行っています。
このリポジトリでカバーできない範囲はまた別にリポジトリを用意してテストします。

# LICENSE

GNU GPL v3です。

Copyright(C) 2019 pCYSl5EDgo<https:github.com/pCYSl5EDgo>

This file is part of UniNativeLinq Test Repository 1.

You can redistribute it and/or modify it under the terms of the GNU General
Public License as published by the Free Software Foundation, either version 3
of the License, or (at your option) any later version.

UniNativeLinq Test Repository 1 is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License along with
UniNativeLinq Test Repository 1. If not, see<http:www.gnu.org/licenses/>.

# Copy

このリポジトリのテストコードはJon Skeet氏のEduLinqを基にしています。

Copyright 2010-2011 Jon Skeet

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at

    http:www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.