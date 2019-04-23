# do_deallocate
* memory_resource[meta header]
* function[meta id-type]
* std::pmr[meta namespace]
* monotonic_buffer_resource[meta class]
* cpp17[meta cpp]

```cpp
void do_deallocate(void* p, size_t bytes, size_t alignment) override;
```

## 概要
[`memory_resource::do_deallocate()`](/reference/memory_resource/memory_resource/do_deallocate.md)の実装。

## 効果
何もしない。

このクラスの管理メモリを解放するには、デストラクタか[`release`](monotonic_buffer_resource/release.md) を呼ぶ必要がある。

## 例外
投げない。

## バージョン
### 言語
- C++17

### 処理系
- [Clang](/implementation.md#clang): ??
- [GCC](/implementation.md#gcc): 9.1
- [Visual C++](/implementation.md#visual_cpp): 2017 update 6

## 関連項目
- [`release`](monotonic_buffer_resource/release.md)
- [`memory_resource`](/reference/memory_resource/memory_resource.md)