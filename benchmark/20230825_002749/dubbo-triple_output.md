# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.155 ops/ms
# Warmup Iteration   2: 2.946 ops/ms
# Warmup Iteration   3: 5.868 ops/ms
Iteration   1: 5.882 ops/ms
Iteration   2: 5.992 ops/ms
Iteration   3: 6.121 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.999 ±(99.9%) 2.180 ops/ms [Average]
  (min, avg, max) = (5.882, 5.999, 6.121), stdev = 0.120
  CI (99.9%): [3.818, 8.179] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.821 ops/ms
# Warmup Iteration   2: 5.409 ops/ms
# Warmup Iteration   3: 6.237 ops/ms
Iteration   1: 6.310 ops/ms
Iteration   2: 6.267 ops/ms
Iteration   3: 6.622 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.400 ±(99.9%) 3.535 ops/ms [Average]
  (min, avg, max) = (6.267, 6.400, 6.622), stdev = 0.194
  CI (99.9%): [2.865, 9.934] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.689 ops/ms
# Warmup Iteration   2: 5.427 ops/ms
# Warmup Iteration   3: 5.866 ops/ms
Iteration   1: 6.065 ops/ms
Iteration   2: 6.124 ops/ms
Iteration   3: 6.271 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.153 ±(99.9%) 1.936 ops/ms [Average]
  (min, avg, max) = (6.065, 6.153, 6.271), stdev = 0.106
  CI (99.9%): [4.218, 8.089] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 1.622 ops/ms
# Warmup Iteration   2: 4.302 ops/ms
# Warmup Iteration   3: 5.159 ops/ms
Iteration   1: 5.242 ops/ms
Iteration   2: 5.357 ops/ms
Iteration   3: 5.308 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.302 ±(99.9%) 1.053 ops/ms [Average]
  (min, avg, max) = (5.242, 5.302, 5.357), stdev = 0.058
  CI (99.9%): [4.250, 6.355] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 16.082 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 5.939 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.461 ±(99.9%) 0.017 ms/op
Iteration   1: 5.221 ±(99.9%) 0.013 ms/op
Iteration   2: 5.111 ±(99.9%) 0.017 ms/op
Iteration   3: 5.557 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.296 ±(99.9%) 4.239 ms/op [Average]
  (min, avg, max) = (5.111, 5.296, 5.557), stdev = 0.232
  CI (99.9%): [1.057, 9.535] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 15.329 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 5.754 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.228 ±(99.9%) 0.009 ms/op
Iteration   1: 5.109 ±(99.9%) 0.012 ms/op
Iteration   2: 4.937 ±(99.9%) 0.013 ms/op
Iteration   3: 5.178 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.075 ±(99.9%) 2.262 ms/op [Average]
  (min, avg, max) = (4.937, 5.075, 5.178), stdev = 0.124
  CI (99.9%): [2.813, 7.336] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 16.406 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 6.030 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.227 ±(99.9%) 0.015 ms/op
Iteration   1: 5.341 ±(99.9%) 0.011 ms/op
Iteration   2: 5.591 ±(99.9%) 0.012 ms/op
Iteration   3: 5.452 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.461 ±(99.9%) 2.291 ms/op [Average]
  (min, avg, max) = (5.341, 5.461, 5.591), stdev = 0.126
  CI (99.9%): [3.170, 7.752] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 17.822 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 7.094 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.286 ±(99.9%) 0.014 ms/op
Iteration   1: 5.957 ±(99.9%) 0.008 ms/op
Iteration   2: 6.155 ±(99.9%) 0.016 ms/op
Iteration   3: 5.868 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.993 ±(99.9%) 2.687 ms/op [Average]
  (min, avg, max) = (5.868, 5.993, 6.155), stdev = 0.147
  CI (99.9%): [3.306, 8.681] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 15.276 ±(99.9%) 0.282 ms/op
# Warmup Iteration   2: 6.243 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.635 ±(99.9%) 0.024 ms/op
Iteration   1: 5.444 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   1.724 ms/op
                 createUser·p0.50:   5.063 ms/op
                 createUser·p0.90:   7.037 ms/op
                 createUser·p0.95:   8.126 ms/op
                 createUser·p0.99:   11.551 ms/op
                 createUser·p0.999:  20.882 ms/op
                 createUser·p0.9999: 25.707 ms/op
                 createUser·p1.00:   26.575 ms/op

Iteration   2: 5.425 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.044 ms/op
                 createUser·p0.50:   5.194 ms/op
                 createUser·p0.90:   6.644 ms/op
                 createUser·p0.95:   7.561 ms/op
                 createUser·p0.99:   10.215 ms/op
                 createUser·p0.999:  26.909 ms/op
                 createUser·p0.9999: 30.314 ms/op
                 createUser·p1.00:   31.064 ms/op

Iteration   3: 5.042 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.890 ms/op
                 createUser·p0.50:   4.817 ms/op
                 createUser·p0.90:   6.160 ms/op
                 createUser·p0.95:   6.816 ms/op
                 createUser·p0.99:   8.978 ms/op
                 createUser·p0.999:  26.136 ms/op
                 createUser·p0.9999: 32.036 ms/op
                 createUser·p1.00:   33.030 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 181135
  mean =      5.297 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 67 
    [ 2.500,  5.000) = 90774 
    [ 5.000,  7.500) = 80796 
    [ 7.500, 10.000) = 7425 
    [10.000, 12.500) = 1289 
    [12.500, 15.000) = 439 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 69 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.724 ms/op
     p(50.0000) =      4.997 ms/op
     p(90.0000) =      6.578 ms/op
     p(95.0000) =      7.569 ms/op
     p(99.0000) =     10.371 ms/op
     p(99.9000) =     21.946 ms/op
     p(99.9900) =     31.126 ms/op
     p(99.9990) =     32.791 ms/op
     p(99.9999) =     33.030 ms/op
    p(100.0000) =     33.030 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 16.101 ±(99.9%) 0.257 ms/op
# Warmup Iteration   2: 5.364 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 5.214 ±(99.9%) 0.018 ms/op
Iteration   1: 5.326 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.982 ms/op
                 existUser·p0.50:   5.046 ms/op
                 existUser·p0.90:   6.619 ms/op
                 existUser·p0.95:   7.578 ms/op
                 existUser·p0.99:   10.479 ms/op
                 existUser·p0.999:  20.999 ms/op
                 existUser·p0.9999: 27.099 ms/op
                 existUser·p1.00:   29.065 ms/op

Iteration   2: 5.040 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.109 ms/op
                 existUser·p0.50:   4.719 ms/op
                 existUser·p0.90:   6.472 ms/op
                 existUser·p0.95:   7.239 ms/op
                 existUser·p0.99:   9.257 ms/op
                 existUser·p0.999:  21.529 ms/op
                 existUser·p0.9999: 24.445 ms/op
                 existUser·p1.00:   25.395 ms/op

Iteration   3: 4.951 ±(99.9%) 0.018 ms/op
                 existUser·p0.00:   1.880 ms/op
                 existUser·p0.50:   4.620 ms/op
                 existUser·p0.90:   6.226 ms/op
                 existUser·p0.95:   7.111 ms/op
                 existUser·p0.99:   9.689 ms/op
                 existUser·p0.999:  20.634 ms/op
                 existUser·p0.9999: 27.299 ms/op
                 existUser·p1.00:   28.901 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 188067
  mean =      5.101 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 48 
    [ 2.500,  5.000) = 113703 
    [ 5.000,  7.500) = 65914 
    [ 7.500, 10.000) = 6617 
    [10.000, 12.500) = 1063 
    [12.500, 15.000) = 346 
    [15.000, 17.500) = 139 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 75 
    [25.000, 27.500) = 66 

  Percentiles, ms/op:
      p(0.0000) =      1.880 ms/op
     p(50.0000) =      4.776 ms/op
     p(90.0000) =      6.447 ms/op
     p(95.0000) =      7.315 ms/op
     p(99.0000) =      9.880 ms/op
     p(99.9000) =     20.995 ms/op
     p(99.9900) =     27.073 ms/op
     p(99.9990) =     29.065 ms/op
     p(99.9999) =     29.065 ms/op
    p(100.0000) =     29.065 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 15.291 ±(99.9%) 0.246 ms/op
# Warmup Iteration   2: 5.657 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 5.627 ±(99.9%) 0.024 ms/op
Iteration   1: 5.431 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.425 ms/op
                 getUser·p0.50:   5.022 ms/op
                 getUser·p0.90:   7.356 ms/op
                 getUser·p0.95:   8.233 ms/op
                 getUser·p0.99:   11.274 ms/op
                 getUser·p0.999:  26.287 ms/op
                 getUser·p0.9999: 29.597 ms/op
                 getUser·p1.00:   30.310 ms/op

Iteration   2: 5.275 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   2.658 ms/op
                 getUser·p0.50:   5.079 ms/op
                 getUser·p0.90:   6.210 ms/op
                 getUser·p0.95:   6.973 ms/op
                 getUser·p0.99:   9.470 ms/op
                 getUser·p0.999:  23.429 ms/op
                 getUser·p0.9999: 29.747 ms/op
                 getUser·p1.00:   30.835 ms/op

Iteration   3: 5.259 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.876 ms/op
                 getUser·p0.50:   5.063 ms/op
                 getUser·p0.90:   6.250 ms/op
                 getUser·p0.95:   6.783 ms/op
                 getUser·p0.99:   8.962 ms/op
                 getUser·p0.999:  24.371 ms/op
                 getUser·p0.9999: 40.402 ms/op
                 getUser·p1.00:   40.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 180294
  mean =      5.321 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 84833 
    [ 5.000, 10.000) = 93712 
    [10.000, 15.000) = 1358 
    [15.000, 20.000) = 161 
    [20.000, 25.000) = 60 
    [25.000, 30.000) = 134 
    [30.000, 35.000) = 4 
    [35.000, 40.000) = 26 
    [40.000, 45.000) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.876 ms/op
     p(50.0000) =      5.054 ms/op
     p(90.0000) =      6.480 ms/op
     p(95.0000) =      7.553 ms/op
     p(99.0000) =      9.961 ms/op
     p(99.9000) =     24.543 ms/op
     p(99.9900) =     37.550 ms/op
     p(99.9990) =     40.698 ms/op
     p(99.9999) =     40.698 ms/op
    p(100.0000) =     40.698 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.230 ±(99.9%) 0.340 ms/op
# Warmup Iteration   2: 7.418 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 6.353 ±(99.9%) 0.023 ms/op
Iteration   1: 6.116 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.785 ms/op
                 listUser·p0.50:   5.767 ms/op
                 listUser·p0.90:   7.438 ms/op
                 listUser·p0.95:   9.011 ms/op
                 listUser·p0.99:   11.567 ms/op
                 listUser·p0.999:  27.787 ms/op
                 listUser·p0.9999: 32.960 ms/op
                 listUser·p1.00:   34.341 ms/op

Iteration   2: 6.019 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   3.052 ms/op
                 listUser·p0.50:   5.702 ms/op
                 listUser·p0.90:   7.365 ms/op
                 listUser·p0.95:   8.266 ms/op
                 listUser·p0.99:   11.698 ms/op
                 listUser·p0.999:  27.554 ms/op
                 listUser·p0.9999: 30.607 ms/op
                 listUser·p1.00:   32.375 ms/op

Iteration   3: 5.995 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.351 ms/op
                 listUser·p0.50:   5.792 ms/op
                 listUser·p0.90:   7.135 ms/op
                 listUser·p0.95:   7.807 ms/op
                 listUser·p0.99:   10.483 ms/op
                 listUser·p0.999:  19.765 ms/op
                 listUser·p0.9999: 26.149 ms/op
                 listUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 158822
  mean =      6.043 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 21065 
    [ 5.000,  7.500) = 124496 
    [ 7.500, 10.000) = 10169 
    [10.000, 12.500) = 2216 
    [12.500, 15.000) = 442 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 21 
    [25.000, 27.500) = 126 
    [27.500, 30.000) = 73 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.351 ms/op
     p(50.0000) =      5.751 ms/op
     p(90.0000) =      7.274 ms/op
     p(95.0000) =      8.323 ms/op
     p(99.0000) =     11.420 ms/op
     p(99.9000) =     26.608 ms/op
     p(99.9900) =     32.120 ms/op
     p(99.9990) =     34.148 ms/op
     p(99.9999) =     34.341 ms/op
    p(100.0000) =     34.341 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.999 ± 2.180  ops/ms
ClientPb.existUser                       thrpt       3   6.400 ± 3.535  ops/ms
ClientPb.getUser                         thrpt       3   6.153 ± 1.936  ops/ms
ClientPb.listUser                        thrpt       3   5.302 ± 1.053  ops/ms
ClientPb.createUser                       avgt       3   5.296 ± 4.239   ms/op
ClientPb.existUser                        avgt       3   5.075 ± 2.262   ms/op
ClientPb.getUser                          avgt       3   5.461 ± 2.291   ms/op
ClientPb.listUser                         avgt       3   5.993 ± 2.687   ms/op
ClientPb.createUser                     sample  181135   5.297 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.724           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.997           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.578           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.569           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.371           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.946           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.126           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.030           ms/op
ClientPb.existUser                      sample  188067   5.101 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.880           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.776           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.447           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.315           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.880           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.995           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.073           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.065           ms/op
ClientPb.getUser                        sample  180294   5.321 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.876           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.054           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.480           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.553           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.961           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.543           ms/op
ClientPb.getUser:getUser·p0.9999        sample          37.550           ms/op
ClientPb.getUser:getUser·p1.00          sample          40.698           ms/op
ClientPb.listUser                       sample  158822   6.043 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.351           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.751           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.274           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.323           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.420           ms/op
ClientPb.listUser:listUser·p0.999       sample          26.608           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.120           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.341           ms/op
