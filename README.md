# MatchView
folk from https://github.com/Rogero0o/MatchView

#what's new
removed unuseful resource to make it a cleaner library.

# How to use
1.Locate to your project direction, key in:

        git submodule add https://github.com/santa222/MatchView


2.added following lines to settings.gradle:

        ':MatchView'
        project (':MatchView').projectDir = new File('MatchView')

3.added lib name to build.gradle for project:

        dependencies {
            ...
            compile project(':MatchView')
        }
