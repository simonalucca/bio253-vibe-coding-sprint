# 📚 Study Planner

A small planner for homework, course to-dos and exams, built during the BIO253 vibe-coding sprint.
It is a single HTML file and runs in any browser with nothing to install.

## 👉 [Try it live](https://simonalucca.github.io/bio253-vibe-coding-sprint/)

**https://simonalucca.github.io/bio253-vibe-coding-sprint/** (no download needed, works on phone too)

## How to run

```bash
git clone https://github.com/simonalucca/bio253-vibe-coding-sprint.git
cd bio253-vibe-coding-sprint
open index.html        # macOS. On Windows/Linux, double-click index.html
```

## Spec (MVP)

1. **Add tasks** with a title, a subject tag, a due date and a type: 📝 *To-do* or 🎓 *Exam*.
2. **Sorted by due date and colour-coded:** 🔴 red = 1 day or less (or overdue), 🟠 orange = less than a week, 🟢 green = a week or more.
3. **Tick off or delete tasks.** A **progress bar per subject** shows how much is done.
4. **Saved automatically** in the browser (localStorage), so tasks are still there after a reload.
5. **One `index.html`, no installation:** clone the repo and open the file.

## Extra features

- 🎓 **Exams stand out** with a purple outline and an EXAM badge. You can filter to show only exams or only to-dos.
- 🍅 **Focus timer (Pomodoro):** click ▶ on a task to run 25 min focus / 5 min break. Each completed focus session is counted on the task. You can change the focus and break minutes under the timer.
- ⬇⬆ **Export / import** tasks as a `.json` file, for example to share a plan with your project partner.
- ✎ **Edit tasks:** change the title, subject, date or type of an existing task (Enter saves, Esc cancels).
- Filter by subject, and hide finished tasks.

## Notes

- Tasks are stored only in *your* browser. Use Export to back them up or move them to another computer.
- Built with plain HTML, CSS and JavaScript, with no frameworks.
