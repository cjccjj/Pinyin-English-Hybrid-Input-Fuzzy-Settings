### **Pinyin-English Hybrid Input Fuzzy Settings Guide**  


**目的与功能 Purpose**  

解决中英混输场景下因英文发音惯性导致的中文拼音输入错误  
*Resolve Chinese Pinyin input errors caused by English pronunciation habits in hybrid typing scenarios*

---

### **一、高度推荐设置 High-Priority Settings**  
#### **声母模糊 Initials Fuzzy**
| 配置规则 Setting Rule | 说明 & 示例 Explanation & Examples                        |
|----------------------|----------------------------------------------------------|
| **c ➔ k**            | c 匹配 k 声母字（例：输入 `cu` 出"哭 ku"）                |
|                      | *c matches k-initial words (e.g. Type `cu` for "哭 ku")* |
| **c ➔ s**            | c 匹配 s 声母字（例：输入 `ci` 出"四 si"）                |
|                      | *c matches s-initial words (e.g. Type `ci` for "四 si")* |
| **g ➔ j**            | g 匹配 j 声母字（例：输入 `gi` 出"机 ji"）                |
|                      | *g matches j-initial words (e.g. Type `gi` for "机 ji")* |

#### **韵母模糊 Finals Fuzzy**
| 配置规则 Setting Rule | 说明 & 示例 Explanation & Examples                        |
|----------------------|----------------------------------------------------------|
| **i ➔ ai**           | i 匹配 ai 韵母字（例：输入 `ki` 出"开 kai"）              |
|                      | *i matches ai-final words (e.g. Type `ki` for "开 kai")* |
| **u ➔ iu**           | u 匹配 iu 韵母字（例：输入 `ju` 出"就 jiu"）             |
|                      | *u matches iu-final words (e.g. Type `ju` for "就 jiu")* |
| **o ➔ u**            | o 匹配 u 韵母字（例：输入 `lo` 出"路 lu"）               |
|                      | *o matches u-final words (e.g. Type `lo` for "路 lu")*  |
| **w ➔ u**            | w 开头匹配零声母u韵字（例：输入 `wou` 出"欧 ou"）        |
|                      | *w-start matches zero-initial u-final (e.g. Type `wou` for "欧 ou")* |

---

### **二、可选配置 Optional Settings**  
#### **声母模糊 Initials Fuzzy**
| 配置规则 Setting Rule | 说明 & 示例 Explanation & Examples                        |
|----------------------|----------------------------------------------------------|
| **s ➔ sh**           | s 匹配 sh 声母字（例：输入 `su` 出"书 shu"）             |
|                      | *s matches sh-initial words (e.g. Type `su` for "书 shu")* |
| **j ➔ zh**           | j 匹配 zh 声母字（例：输入 `ja` 出"炸 zha"）             |
|                      | *j matches zh-initial words (e.g. Type `ja` for "炸 zha")* |

#### **韵母模糊 Finals Fuzzy**
| 配置规则 Setting Rule | 说明 & 示例 Explanation & Examples                        |
|----------------------|----------------------------------------------------------|
| **u ➔ ou**           | u 匹配 ou 韵母字（例：输入 `gu` 出"狗 gou"）             |
|                      | *u matches ou-final words (e.g. Type `gu` for "狗 gou")* |
| **e ➔ i**            | e 匹配 i 韵母字（例：输入 `xe` 出"西 xi"）               |
|                      | *e matches i-final words (e.g. Type `xe` for "西 xi")*  |
| **a ➔ ei**           | a 匹配 ei 韵母字（例：输入 `ma` 出"美 mei"）             |
|                      | *a matches ei-final words (e.g. Type `ma` for "美 mei")* |
| **oo ➔ u**           | oo 匹配 u 韵母字（例：输入 `shoo` 出"书 shu"）           |
|                      | *oo matches u-final words (e.g. Type `shoo` for "书 shu")* |

> **注**：一般配置可能增加候选词数量，建议按需开启  
> *Note: Optional settings may increase candidate words, enable based on need*

---

### **三、设置方法 Configuration Steps**  
#### **支持输入法 Supported IMEs**
| 输入法名称 IME          | 设置路径 Configuration Path               |
|--------------------------|------------------------------------------|
| 搜狗拼音 Sogou Pinyin    | 设置 > 高级 > 模糊音设置                 |
|                          | *Settings > Advanced > Fuzzy Pinyin*     |
| 百度输入法 Baidu IME     | 设置 > 输入设置 > 智能纠错               |
|                          | *Settings > Input Settings > Auto-Correct* |
| 讯飞输入法 iFlytek       | 设置 > 智能输入 > 模糊音                 |
|                          | *Settings > Smart Input > Fuzzy Pinyin*  |
| 微软拼音 Microsoft Pinyin| Windows设置 > 模糊拼音                   |
|                          | *Windows Settings > Fuzzy Pinyin*        |

#### **操作说明 Instructions**
1. 优先开启 **高度推荐** 项目  
   *Enable High-Priority items first*  
2. 按需添加 **一般配置** 项目  
   *Add Optional items based on personal needs*  
3. 按需关闭或调整方言等其他模糊项（如 z/zh, n/l）  
   *Adjust or Disable dialect or other fuzzy sets (e.g. z/zh, n/l)*  
4. 部分规则需重启输入法生效  
   *Some rules require IME restart*  
