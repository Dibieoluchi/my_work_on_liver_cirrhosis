# my_work_on_liver_cirrhosis
CIRRHOSIS LIVER DISEASE ANALYSIS
CONTEXT

AIM : THE AIM OF THIS DISEASE ANALYSIS IS TO DETERMINE THE VARIOUS FACTORS THAT LEAD TO THE CIRRHOSIS OF THE LIVER

The liver performs several crucial functions:

it filters toxins from the blood,
metabolizes drugs, stores energy,
fights infections, and helps with digestion.
This football-sized organ is incredibly resilient, with the ability to repair and regenerate itself in order to continue performing its necessary functions.

That being said, your largest internal organ isn’t invincible. A liver that is constantly working too hard can end up with liver damage; repeated liver damage can lead to liver disease. While the liver may be able to heal itself in the early stages of disease, the damage will become progressively worse and irreversible over time.

Cirrhosis is a late stage of scarring (fibrosis) of the liver caused by many forms of liver diseases and conditions, such as hepatitis and chronic alcoholism. The following data contains the information collected from the Mayo Clinic trial in primary biliary cirrhosis (PBC) of the liver conducted between 1974 and 1984. source

418 PBC patients participated in randomized placebo-controlled trial of the drug D-penicillamine

312 cases participated in the randomized trial

106 cases did not participate in the clinical trial (6 of the original 112 were lost)

The dataset consists of following columns :

ID: unique identifier [id]

N_Days: number of [days] between registration and the earlier of death, transplantation, or study analysis time in July 1986

Status: status of the patient [C, CL, or D] C (censored), CL (censored due to liver tx), or D (death)

Drug: type of drug [D-penicillamine or placebo]

Age: age in [days]

Sex: [M or F] M (male) or F (female)

Ascites: presence of ascites [N or Y] N (No) or Y (Yes)

Hepatomegaly: presence of hepatomegaly [N or Y] N (No) or Y (Yes)

Spiders: presence of spiders [N or Y] N (No) or Y (Yes)

Edema: presence of edema [N, S, or Y] N (no edema and no diuretic therapy for edema), S (edema present without diuretics, or edema resolved by diuretics), or Y (edema despite diuretic therapy)

.... we have the presence of the following serum in a patient blood level below which will help in determining the chances of liver cirrhosis in a patient

Bilirubin: serum bilirubin in [mg/dl]

Cholesterol: serum cholesterol in [mg/dl]

Albumin: albumin in [gm/dl]

Copper: urine copper in [ug/day]

Alk_Phos: alkaline phosphatase in [U/liter]

SGOT: SGOT in [U/ml]

Triglycerides: triglicerides in [mg/dl]

Platelets: platelets per cubic [ml/1000]

Prothrombin: prothrombin time in seconds [s]

Stage: histologic stage of disease [1, 2, 3, or 4]

reference for my project: https://www.kaggle.com/code/arjunbhaybhang/liver-cirrhosis-prediction-with-xgboost-eda

data site
