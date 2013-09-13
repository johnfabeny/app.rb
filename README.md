require 'sinatra'
 
class ConcreteApp < Sinatra::Base
 set :protection, :except => :frame_options
 
 post '/' do
 "Hello World"
 end
end
