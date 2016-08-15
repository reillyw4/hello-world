puts "Is this a plain text editor?"
answer = gets.chomp
answer.downcase!

if answer == yes
  puts "Well then Hello World!"
else
  puts "Then why am I using it?"
end
