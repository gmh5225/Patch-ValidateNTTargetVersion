# Patch-ValidateNTTargetVersion
Fix "The "ValidateNTTargetVersion" task could not be loaded" in VS2015

## Error
```
The "ValidateNTTargetVersion" task could not be loaded from the assembly C:\Program Files (x86)\Windows Kits\10\build\\bin\Microsoft.DriverKit.Build.Tasks.14.0.dll.  Confirm that the <UsingTask> declaration is correct, that the assembly and all its dependencies are available, and that the task contains a public class that implements Microsoft.Build.Framework.ITask.
```

## Fix
Replace file ``"C:\Program Files (x86)\Windows Kits\10\build\WindowsDriver.Common.targets"`` to [WindowsDriver.Common.targets](https://github.com/gmh5225/Patch-ValidateNTTargetVersion/blob/main/WindowsDriver.Common.targets).
