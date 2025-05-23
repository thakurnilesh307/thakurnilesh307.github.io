import React, { useState } from "react";

const UserFormSlideshow = () => {
  const [formData, setFormData] = useState({
    name: "",
    age: "",
    location: "",
    gender: "",
  });

  const [step, setStep] = useState(0);

  const steps = [
    {
      label: "Name",
      type: "text",
      name: "name",
      value: formData.name,
    },
    {
      label: "Age",
      type: "number",
      name: "age",
      value: formData.age,
    },
    {
      label: "Location",
      type: "text",
      name: "location",
      value: formData.location,
    },
    {
      label: "Gender",
      type: "select",
      name: "gender",
      value: formData.gender,
    },
  ];

  const handleChange = (e) => {
    const { name, value } = e.target;
    setFormData((prev) => ({
      ...prev,
      [name]: value,
    }));
  };

  const nextStep = () => {
    if (step < steps.length - 1) {
      setStep(step + 1);
    }
  };

  const prevStep = () => {
    if (step > 0) {
      setStep(step - 1);
    }
  };

  const handleSubmit = (e) => {
    e.preventDefault();
    alert(`Submitted:\nName: ${formData.name}\nAge: ${formData.age}\nLocation: ${formData.location}\nGender: ${formData.gender}`);
  };

  return (
    <form
      onSubmit={handleSubmit}
      className="max-w-md mx-auto mt-10 p-6 bg-white rounded shadow space-y-6"
    >
      <h2 className="text-xl font-semibold text-center">Step {step + 1} of {steps.length}</h2>

      <div className="space-y-2">
        <label className="block text-sm font-medium">
          {steps[step].label}
        </label>

        {steps[step].type === "select" ? (
          <select
            name={steps[step].name}
            value={steps[step].value}
            onChange={handleChange}
            className="w-full border px-3 py-2 rounded"
            required
          >
            <option value="">Select...</option>
            <option value="male">Male</option>
            <option value="female">Female</option>
            <option value="nonbinary">Non-binary</option>
            <option value="preferNotToSay">Prefer not to say</option>
          </select>
        ) : (
          <input
            type={steps[step].type}
            name={steps[step].name}
            value={steps[step].value}
            onChange={handleChange}
            className="w-full border px-3 py-2 rounded"
            required
          />
        )}
      </div>

      <div className="flex justify-between">
        <button
          type="button"
          onClick={prevStep}
          disabled={step === 0}
          className="px-4 py-2 bg-gray-300 rounded hover:bg-gray-400 disabled:opacity-50"
        >
          Back
        </button>

        {step < steps.length - 1 ? (
          <button
            type="button"
            onClick={nextStep}
            className="px-4 py-2 bg-blue-500 text-white rounded hover:bg-blue-600"
          >
            Next
          </button>
        ) : (
          <button
            type="submit"
            className="px-4 py-2 bg-green-500 text-white rounded hover:bg-green-600"
          >
            Submit
          </button>
        )}
      </div>
    </form>
  );
};

export default UserFormSlideshow;
