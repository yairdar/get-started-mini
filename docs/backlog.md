# Backlog

## Researcher Commands List

### Management Tasks

```noml
management tasks
  ssh RnD
    code
      task shell-RnD
      task code-RnD
      task emacs-RnD
      task sync-RnD-Work-repos
      task sync-RnD-Work-drafts
        sync targets
          datasets
          repos
          drafts
          ephemera
            saved features
            learning
            logs
            history
```


### DashBoards and Monitoring tasks

```noml
task
  task connect
  task shell
  task sync
  task execute
    run pipeline
      show logs
        bring up dashboard # clj -M serve&show (clerk/serve! clerk/show!)
          _comment_: status pings & expectations & deltas
            ping everything running over 20 minutes and display status
                        ping everything with uptime over...
                        ping everything with results newer than...
                        summarize everything with results older than...
        analyze
          summarize
          browse
            interact
              replay
              zoom
              aggregate
              predict
              watch
              ping
    deploy ...
    presets
    flush keys
    run a batch job and notify me when it runs
    update dashboard and notify me
      show logs
      run pipeline
      orchestrate
        manage
          presets
          dashboard
          Resource
            Instances
            Environments
              Runtimes
              Interactive
                Instance
                  Container
                    Shell
            Automations
              *mappable patterns*
                task
                presets
```