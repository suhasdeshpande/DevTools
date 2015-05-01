[user]
        name = Suhas Deshpande
        email = suhas2u@gmail.com
[color]
        ui = auto
        interactive = auto
[color "branch"]
        current = yellow reverse
        local = yellow
        remote = green
[color "diff"]
        meta = yellow bold
        frag = magenta bold
        old = red bold
        new = green bold
[color "status"]
        added = cyan bold
        changed = red
        untracked = magenta bold
[alias]
        co = checkout
        m = merge
        cp = cherry-pick
        f = fetch
        fo = fetch origin
        rom = rebase origin/master
        rbm = rebase master
        rbi = rebase --interactive
        rbc = rebase --continue
        rbs = rebase --skip
        rba = rebase --abort
        st = status -s
        ci = commit
        br = branch
        lol = log --graph --date=relative --pretty=format:"%C(Yellow)%h%x20%C(Blue)%an%C(Red)%d%x20%C(Green)-%x20%s%x20%C(Cyan)%cd"
[push]
        default = simple
~