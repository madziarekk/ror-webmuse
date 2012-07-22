puts "hello!"

#
#max z tablicy
puts [12,47,35].max
ticket = [12,47,35]
puts ticket.sort

puts Dir["/*.txt"]
puts Dir["*.rb"]
print File.read("file.rb")


def load_comics( path )
  comics = {}
  File.foreach(path) do |line|
    name, url = line.split(': ')
    comics[name] = url.strip
  end
  comics
end


class BlogEntry
  def initialize( title, mood, fulltext )
    @time = Time.now
    @title, @mood, @fulltext = title, mood, fulltext
  end
end


entry = BlogEntry.new

puts entry