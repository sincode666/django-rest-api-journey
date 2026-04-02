Serializers

## Overview
Serializers convert complex data into JSON and vice versa.

## Purpose

- Model → JSON (for response)
- JSON → Model (for saving data)

## Example

#python
class StudentSerializer(serializers.ModelSerializer):
    class Meta:
        model = Student
        fields = '__all__'