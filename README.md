# Julia
## Certificates
- [x] https://app.datacamp.com/profile/lvhkhanh
- [x] introduction-to-julia https://www.datacamp.com/statement-of-accomplishment/course/f0751a2e1d9c67906122b0c5ff102e40a431438f
## Courses
- [x] https://campus.datacamp.com/courses/introduction-to-julia

```
index based 1
str = "AB"
str[1] # 'A' char not string
str[end] # 'B'
#=
block comments
println(1);
=#
use other unicode chars like alpha, beta for variable names
string(1) # "1" <> '1' , small string not String
parse(Int64, "1") # 1
string1 concat string 2: string1 * string2
multiline string """
one line
two line """
"interpolation $var"
# data structure
dict = Dict("key" => true, "key2" => "value")
a = 1
i = 0 # iterattor
while i < a
  global a = a + i # global
  i += 1
end
# Vector: 1D array
arr = [false, 1, "2", 3.14]
typeof(arr) # Vector{Any}
# Matrix: 2D array
# Mutating function with ! vs non mutating function
push!(arr, 1)
el = pop!(arr)
append!(arr, [1,2])
function apply(el)
  return el * 2
end
apply.([1,2]) # [2,4]
# multiple dispatch vs overloading
function apply(x)
end
function apply(x::String)
end
```
