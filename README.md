# Check-in-Dance
Dance steps:

1. Run tests
    ./gradlew clean build

2. Check CI (green)

3. Pull (code base up-to-date)
    git pull --rebase

4. Run tests
    ./gradlew clean build

5. Make changes (red-green-refactor)

6. Run tests
    ./gradlew clean build

7. Commit to local
    git add <filename> -A
    git commit -m "your commit message"

8. Check CI (green)

9. Pull
    git pull --rebase

    If there are merge conflicts:
	a) Fix files with conflicts
	b) git add <fixed files>
	c) git rebase --continue

10. Run tests
    ./gradlew clean build

11. Push
    git push
    
12. Push
    Check CI
