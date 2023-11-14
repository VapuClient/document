## module

### 属性

#### getName(): String
获取模块的名称。

- 返回值: 模块的名称 (类型: `String`)。

#### getCategory(): category
获取模块的所属分类。

- 返回值: `Category` 对象，表示模块所属的分类。

#### isScriptModule(): boolean
检查模块是否为脚本模块。

- 返回值: 如果模块是脚本模块，则返回 `true`；否则返回 `false` (类型: `boolean`)。

#### getKey(): int
获取模块的绑定键（按键码）。

- 返回值: 模块的绑定键 (类型: `int`)。

#### getState(): boolean
获取模块的状态，表示模块是否启用。

- 返回值: 如果模块已启用，则返回 `true`；否则返回 `false` (类型: `boolean`)。

#### getSuffix(): String
获取模块的后缀信息。

- 返回值: 模块的后缀信息 (类型: `String`)。

### 方法

#### getOption(name: String): value
获取模块的选项值（AbstractValue）。

- 参数:
  - `name` (类型: `String`) - 选项的名称。

- 返回值: `Value` 对象，表示指定选项的值。

#### getOptions(): List
获取模块的所有选项值（AbstractValue）。

- 返回值: 包含所有选项值的 `value` 对象列表。

#### addOption(v: value): void
向模块添加一个选项值。

- 参数:
  - `v` (类型: `value`) - 要添加的选项值。

#### toggle(): void
切换模块的状态，启用时将禁用，禁用时将启用。

#### setKey(key: int): void
设置模块的绑定键（按键码）。

- 参数:
  - `key` (类型: `int`) - 要设置的绑定键。

#### setSuffix(s: String): void
设置模块的后缀信息。

- 参数:
  - `s` (类型: `String`) - 要设置的后缀信息。

