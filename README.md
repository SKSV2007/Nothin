# Nothin
{
    "tool": "Credential Scanner",
    "suppressions": [
        {
            "file": "\\src\\Calculator\\WindowsDev_TemporaryKey.pfx",
            "_justification": "This is an untrusted, self-signed certificate which is used only during development. Its private key is not intended to be secret."
        },
        {
            "file": "\\src\\CalculatorUnitTests\\WindowsDev_TemporaryKey.pfx",
            "_justification": "This is an untrusted, self-signed certificate which is used only during development. Its private key is not intended to be secret."
        }
    ]
}
