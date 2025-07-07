# 💾 7 DAILY BACKUPS

## Purpose
Your divine insurance policy - protecting months of sacred work from digital disasters

## What Goes Here
- Complete daily copies of your entire project
- Dated folders with full snapshots
- Export packages from Unity
- Database backups
- Source art file archives
- Build executables for testing
- Progress screenshots/videos
- Development journal entries

## Folder Structure Inside
```
7 daily backups\
├── 2024_11_04\
│   ├── unity_backup.zip      (Entire game project)
│   ├── art_backup.zip        (All artwork)
│   ├── contracts_backup.zip  (Smart contracts)
│   ├── build_v0.1.exe       (Playable build)
│   ├── screenshots\          (Today's progress pics)
│   └── dev_journal.txt       (What you accomplished)
├── 2024_11_05\
├── 2024_11_06\
└── [continues daily...]
```

## Use Cases
- Disaster recovery (corrupted files, hardware failure)
- Version history tracking
- Sharing specific builds with testers
- Portfolio documentation
- Reverting failed experiments
- Cloud backup preparation
- Progress milestone tracking
- "Remember when it looked like this?" moments

## Daily Backup Ritual (Every Night at 10 PM)

### Quick Backup Script
Create `backup_today.bat` in main folder:
```batch
@echo off
set TODAY=%date:~-4%_%date:~4,2%_%date:~7,2%
set BACKUP_DIR="D:\biblical chronicles game\7 daily backups\%TODAY%"

echo Creating backup for %TODAY%...
mkdir %BACKUP_DIR%
mkdir %BACKUP_DIR%\screenshots

echo Copying Unity project...
xcopy "D:\biblical chronicles game\1 game project" "%BACKUP_DIR%\unity_backup" /E /I /Q

echo Copying artwork...
xcopy "D:\biblical chronicles game\2 character art" "%BACKUP_DIR%\art_backup" /E /I /Q
xcopy "D:\biblical chronicles game\3 background art" "%BACKUP_DIR%\art_backup" /E /I /Q

echo Backup complete! Don't forget to:
echo 1. Take a screenshot of today's progress
echo 2. Write in dev_journal.txt what you accomplished
pause
```

## What to Document Daily

### dev_journal.txt Template
```
Date: November 4, 2024
Hours Worked: 3.5

ACCOMPLISHED TODAY:
- Created Adam sprite (innocent and fallen versions)
- Implemented basic movement in Unity
- Set up project folder structure
- Added scripture display system

TOMORROW'S GOALS:
- Add Eve character
- Create Garden of Eden background
- Implement tree interaction

PROBLEMS SOLVED:
- Fixed sprite pixelation (changed filter to Point)
- Resolved Unity input system issue

LESSONS LEARNED:
- Keep sprites at 64x64 for consistency
- Test builds every major change

PRAYER REQUESTS:
- Wisdom for character design
- Strength to maintain Biblical accuracy
```

## Screenshot Guidelines
Always capture:
1. **New character sprites** in Krita
2. **Unity scene view** progress
3. **Working gameplay** (GIF if possible)
4. **Any visual bugs** (for debugging later)
5. **Successful milestones** (first NPC, etc.)

## Cloud Backup Strategy
Weekly upload to:
- Google Drive (free 15GB)
- OneDrive (free 5GB)
- GitHub (code only, not art)
- External USB drive

## Recovery Instructions
If disaster strikes:
1. Find most recent backup folder
2. Copy entire contents back to main folders
3. Open Unity and let it reimport
4. You've lost maximum 1 day of work!

## Milestone Backups
Special archives for major moments:
- `MILESTONE_first_playable_demo.zip`
- `MILESTONE_all_genesis_complete.zip`
- `MILESTONE_nft_integration_working.zip`
- `MILESTONE_beta_release_v1.zip`

## Storage Management
- Keep daily backups for 1 month
- Then keep weekly backups for 6 months
- Archive monthly backups forever
- Each full backup ≈ 500MB-1GB

## Remember
"The prudent see danger and take refuge, but the simple keep going and pay the penalty." - Proverbs 27:12

**BACKUP EVERY NIGHT. NO EXCEPTIONS.**