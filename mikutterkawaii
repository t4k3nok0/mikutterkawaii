# -*- coding: utf-8 -*-

Plugin.create(:mikutterkawaii) do
	command(:mikutterkawaii ,
      	name: 'mikutterかわいい',
      	condition: lambda{ |opt| true },
      	visible: true,
      	role: :timeline)do |opt|
	kazu = rand(2147483647) + 1
	text1 = "mikutterとカナブンめっちゃかわいい("
	text2 = "回目ぐらい) #mikutterとカナブンめっちゃかわいい"
	Service.primary.update(:message => text1 + kazu.to_s + text2)
	
	end
end
