# ascendium-interview
interview question


temp = 1
n = 5
space = 0
arr = []
while n > 0
  t1 = '* ' * n
  t2 = ' ' * space
  arr << "#{t2}#{t1}"
  space += 1
  n -= 1
end

puts arr
puts arr.reverse
