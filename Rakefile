require 'neography/tasks'
require './neo_holdings.rb'

namespace :neo4j do
  task :scrape do
#    scrape_symbols
    scrape_holdings
  end

  task :create do
    create_graph
  end
end