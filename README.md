ruby-assignment
===============

Rub Assignment 1
#irb
added_phrase = "Only in America!"
puts "Any phrase plus #{added_phrase}!"
end

#irb
array =[100, 10, -10]
array.max
end

#irb
array1 = [:toyota, :tesla]
array2 = ["Prius", "Models"]
puts "#[array1[0],array2[0],array1[1],array2[1]]


def fizzbuzz
    100.times do |n|
        if (n+1) %3 == 0 && (n+1) %5 == 0
            puts "FIZZBUZZ"
            elsif (n+1) %3 ==0
            puts "Fizz"
            elsif (n+1) %5 == 0
            puts "Buzz"
            else 
            puts n + 1
        end
    end
end
