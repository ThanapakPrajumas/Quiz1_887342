# Quiz1_887342
US_states = 
{"Alabama" => "AL",
"Alaska" => "AK",
"Arizona" => "AZ",
"Arkansas" => "AR",
"California" => "CA",
"Colorado" => "CO",
"Connecticut" => "CT",
"Delaware" => "DE",
"District of Columbia" => "DC",
"Florida" => "FL",
"Georgia" => "GA",
"Hawaii" => "HI",
"Idaho" => "ID",
"Illinois" => "IL",
"Indiana" => "IN",
"Iowa" => "IA",
"Kansas" => "KS",
"Kentucky" => "KY",
"Louisiana" => "LA",
"Maine" => "ME",
"Maryland" => "MD",
"Massachusetts" => "MA",
"Michigan" => "MI",
"Minnesota" => "MN",
"Mississippi" => "MS",
"Missouri" => "MO",
"Montana" => "MT",
"Nebraska" => "NE",
"Nevada" => "NV",
"New Hampshire" => "NH",
"New Jersey" => "NJ",
"New Mexico" => "NM",
"New York" => "NY",
"North Carolina" => "NC",
"North Dakota" => "ND",
"Ohio" => "OH",
"Oklahoma" => "OK",
"Oregon" => "OR",
"Pennsylvania" => "PA",
"Rhode Island" => "RI",
"South Carolina" => "SC",
"South Dakota" => "SD",
"Tennessee" => "TN",
"Texas" => "TX",
"Utah" => "UT",
"Vermont" => "VT",
"Virginia" => "VA",
"Washington" => "WA",
"West Virginia" => "WV",
"Wisconsin" => "WI",
"Wyoming" => "WY"}
US_states.each do |k,v|
1.if(v[1]=="T"||v[1]=="N")
puts "#{k}","#{v}"
end
end
puts US_states.sort.reverse
US_states.each do |k,v|
v=['a','e','i','o','u']
if (v.include?k.downcase[0])&&(v.include?k.downcase[-1])
puts "#{k}"
end
end

2.require 'prime' num = gets.chomp n = 1 Prime.each(num.to_i) do |prime| print "p#{n} -> #{prime}, " n += 1 end
