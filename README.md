=begin
Code-Academy-Bug-rollback-account-code-backup
my account in code academy starting get some roll back so i solved "save" the progress
=end

#Thith Meanth War!

print ("hey name?")
user_input = gets.chomp
user_input.downcase!
if user_input.include? "s"
   print ("content s")
   user_input.gsub!(/s/, "th")
   print ("now all [s] turned into [th]")
   else
       print (0)
       puts "the string: #{user_input}"
end
