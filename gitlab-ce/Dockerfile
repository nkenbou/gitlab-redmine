FROM gitlab/gitlab-ce:latest
MAINTAINER Kenichi Sone <nkenbou@gmail.com>

RUN sed -i -e '/storage_directory git_data_directory do/,/end/ s/mode "[0-9]\+"/mode "0750"/ ' /opt/gitlab/embedded/cookbooks/gitlab/recipes/gitlab-shell.rb
