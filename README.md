# godbolt-toys
Experiments, Tutorials, Examples written for myself and colleagues

* Initialization
  * https://godbolt.org/z/65oMjB - Default/Zero/Value initialize
  * https://godbolt.org/z/b_8yEQ - Default/Zero/Value initialize
* Pass-key idiom
  * https://gcc.godbolt.org/z/t4IwpC - For shared_from_this
* Argument passing
  * https://godbolt.org/z/ashjrf - Pass shared_ptr args by l-value, reference, and r-value
* Parameter Pack Manipulation
  * https://godbolt.org/z/6xdr3ndT7 - Selecting arguments from pack 
* Fold expressions
  * https://godbolt.org/z/dx18xj - all_of(), any_of(), none_of()
  * https://godbolt.org/z/1b5sYe - is_any_of(), matches_any_of()
  * https://godbolt.org/z/baEEov - is()
* StaticPointerArray / TriangleArray
  * https://godbolt.org/z/TdYnz5hTY
* Monads
  * https://godbolt.org/z/4PK6Pq - M, MChain
  * https://godbolt.org/z/hKq8PW
  * https://godbolt.org/z/Wqn6q6
* #pragma clang
  * https://godbolt.org/z/46zsd3 - -Wenum-switch
* GMock
  * https://godbolt.org/z/zMfTqq - VerifyAndClearExpectations
  * https://godbolt.org/z/K3TczsEcK - Container matchers
  * https://godbolt.org/z/55c7G5 - std::optional matcher
* Boost
  * https://godbolt.org/z/n3d9jz - UUID
  * https://godbolt.org/z/c48jMK - Scoped Exit
  * https://godbolt.org/z/sGrbEr, https://godbolt.org/z/WbeqMY, https://godbolt.org/z/7PbPnd - synchronized_value
  * https://godbolt.org/z/cK5fE3 - Iterators
  * https://godbolt.org/z/zezjzG - Range utils
  * https://godbolt.org/z/sP8ssa - Small Vector
  * https://godbolt.org/z/arfPz6 - case insensitive map
  * https://godbolt.org/z/5KcqqfE5c - tokenizer
* Boost Ranges
  * https://godbolt.org/z/9GToW5rhY - Take First N adaptor
  * https://godbolt.org/z/j6YKGx - optional filtered
  * https://godbolt.org/z/c3WzPecG3 - chunked
* C++17 features (presentation)
  * https://godbolt.org/z/3t6rWW, https://godbolt.org/z/tGbDOs, https://godbolt.org/z/tGbDOs, https://godbolt.org/z/Cq7CeE, https://godbolt.org/z/wgj2mH, https://godbolt.org/z/4ifc2v - structured binding
  * https://godbolt.org/z/qRDXWW, https://godbolt.org/z/adoyMf - CTAD
  * https://godbolt.org/z/_LZiG8 - inline static init
  * https://godbolt.org/z/YBcjXH - single line namespace
  * https://godbolt.org/z/ueBtdz - optional
  * https://godbolt.org/z/6FYfbN - if constexpr (https://godbolt.org/z/oFaPbF)
  * https://godbolt.org/z/bSHsim - string_view (https://godbolt.org/z/2tPunP)
  * https://godbolt.org/z/HDxqr7, https://godbolt.org/z/uvTdBN - if inti
  * https://godbolt.org/z/z4SRYH - variant
* Misc 
  * https://godbolt.org/z/r7TE4a - Optional Visitor
  * https://godbolt.org/z/v1c39PEbc - Embedded Python
  * https://godbolt.org/z/YY8n5qn4o - Embedded Lua
  *   



# Quick Bench

* https://quick-bench.com/q/Tb0hKu3-y1rtGk8QBgNpoOJqe6s make_move_iterator
* https://quick-bench.com/q/zKBLlNZ1RW3BdM8f7z05MbRKFbM return string vs string_view
* https://quick-bench.com/q/ueiPnVIqct_QS5KJcqeGMO4EdNU pass shared_ptr by-value vs by-ref
