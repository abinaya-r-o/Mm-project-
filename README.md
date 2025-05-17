IBM -AI- EBPL- Healthcare diagnostics and treatment 
import random
Mock database of symptoms and conditions
symptom_rules = 1
"fever": ["flu": 3, "covid": 4, "malaria": 51.
"cough": ["flu": 2. "covid": 5, "asthma": 11.
"fatigue" ["anemia": 4, "flu": 21.
"headache": ["migraine": 5, "flu": 21.
treatment_guidelines = (
5/12
"flu": "Rest, hydration, over-the-counter medication, consult if persistent.".
"covid": "Isolation, hydration, paracetamol, consult for breathing issues.".
"malaria": "Consult doctor, antimalarial medication required.".
"anemia": "Iron supplements, balanced diet, follow-up with dector.".
"migraine": "Pain relievers, avoid triggers, rest in dark room.".
"asthma" "Inhaler. avoid allergens, seek medical advice for severe cases.".
def collect_symptoms():
print("Enter your symptoms one by one. Type 'done' when finished")
def simulate_lot_data():
return |
"heart rate": random.randint(60, 120).
"oxygen level": random.randint(85, 100).
"body temp": round(random.uniform(36.0, 39.5), 1).
def check_anomalies(iot_data):
alerts = []
if ist data["heart_rate"] > 100:
alerts.append("High heart rate detected.")
if lot_data["oxygen level"] <92:
alerts.append("Low oxygen level detected.")
if ist datal body.temp"] > 38.0
alerts.append("Fever detected.")
return alerts
def main():
print("Welcome to the Healthcare Diagnostics and Treatment
System\n")
symptoms collect_symptoms()
scores evaluate_symptoms/symptoms)
treatment recommend treatment[scores)
print("\nDiagnosis Result")
print(treatment)
Optional leT Integration
print("\nSimulating lot device input...")
tot data simulate_ist_data()
printff leT Readings: list_datal")
anomalies check_anomalies(ist_data)
If anomalies
print("Alertss")
if ist data["heart_rate"] > 100
alerts.append("High heart rate detected.")
if ist data["oxygen_level"] <921
alerts.append("Low oxygen level detected.")
If iot_data["body temp"] > 38.01
alerts.append("Fever detected.")
return alerts
def main():
print("Welcome to the Healthcare Diagnostics and Treatment
System\n")
symptoms collect_symptoms()
scores = evaluate_symptoms/symptoms)
treatment = recommend_treatment(scores)
print("\nDiagnosis Results")
print(treatment)
print("\nSimulating lot device input...")

ist_data simulate_ist_data()

print(f"loT Readings: liet datal")

anomalies check_anomalieslist_data)

if anomalies:

print("Alerts")

for alert in anomalies:

print(f"-lalert!")

7/12

3

print("\nDisclaimer: This tool provides guidance only and is not a substitute for professional medical advice.")

if_name="main":

main()

def collect symptoms():

print("Enter your symptoms one by one. Type 'done when finished")

user_symptoms = []

while True:
symptom = input("Symptoms ").strip().lower()
if symptom == 'done's
break
user_symptoms.append(symptom)
return user symptoms
def evaluate symptoms(symptoms)
scores = 11
for symptom in symptoms
if symptom in symptom_rules
for condition, score in symptom_rules[symptom].items():
scores[condition] = scores.get(condition. Ol score
return scores
def recommend treatment(diagnosis_scores)
If not diagnosis scores! osis_scores!
return "No matching diagnosis found. Please consult a healthcare provider."
top_condition = max(diagnosis scores, key=diagnosis scores.get)
guidance treatment_guidelines.get{top_condition. "Consult a doctor for treatment.")
return f"Most likely condition (top_condition_title())
nRecommended Treatment: Iguidancel" \
def simulate_tot_data():
return 1
"heart rate" random.randint(50, 120),
"oxygen level" random.randint(85. 1001.
"body temps round(random.uniform(36.0. 39.5), 1).
