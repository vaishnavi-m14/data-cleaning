# data-cleaning
Cleaning Medical Appointment No-Shows dataset
##  Tools Used
- Microsoft Excel (All cleaning done without coding)

##  Cleaning Steps
1. **Duplicate Removal**  
   - Used: `Data → Remove Duplicates`  
   - Removed: 301 duplicate appointments  
2. **Removed duplicate rows**
   - Used: Data → Remove Duplicates (50,301 duplicates removed)
3. **Fixed column names**  
   - Changed spaces to underscores (e.g., `Patient ID` → `Patient_ID`)
4. **Standardized dates**  
   - Formatted all dates as `DD-MMM-YYYY` (e.g., 01-Apr-2023)

  ## 💡 Why These Changes Matter
- **No spaces in column names** → Prevents errors in data tools  
- **Consistent dates** → Makes filtering/analysis easier  
- **No duplicates** → Ensures accurate patient counts 
