# github-composit-action
This repo contains how to create github custom actions


# Steps to create custom action

1. Clone this repo 
2. Update the create goodbye.sh
3. add following example code in file mentioned above
  echo "Goodbye"
4. Run git command : 
    git add goodbye.sh
    git commit -m "Add goodbye script"
    git push
5. Add action.yml file as available in this repo
6. Run git command : 
    git add action.yml
    git commit -m "Add action"
    git push
    git tag -a -m "Description of this release" v1
    git push --follow-tags
 
 7. Add test action workflow to uer custom created action. Take the ref from workflow available in this repo
 


