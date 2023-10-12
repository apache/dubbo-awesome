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
# Warmup Iteration   1: 1.726 ops/ms
# Warmup Iteration   2: 3.812 ops/ms
# Warmup Iteration   3: 7.394 ops/ms
Iteration   1: 7.489 ops/ms
Iteration   2: 7.934 ops/ms
Iteration   3: 7.949 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.791 ±(99.9%) 4.769 ops/ms [Average]
  (min, avg, max) = (7.489, 7.791, 7.949), stdev = 0.261
  CI (99.9%): [3.021, 12.560] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 2.229 ops/ms
# Warmup Iteration   2: 7.093 ops/ms
# Warmup Iteration   3: 8.077 ops/ms
Iteration   1: 8.083 ops/ms
Iteration   2: 8.230 ops/ms
Iteration   3: 8.361 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.225 ±(99.9%) 2.539 ops/ms [Average]
  (min, avg, max) = (8.083, 8.225, 8.361), stdev = 0.139
  CI (99.9%): [5.686, 10.763] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.240 ops/ms
# Warmup Iteration   2: 7.088 ops/ms
# Warmup Iteration   3: 7.787 ops/ms
Iteration   1: 7.854 ops/ms
Iteration   2: 8.284 ops/ms
Iteration   3: 7.874 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.004 ±(99.9%) 4.431 ops/ms [Average]
  (min, avg, max) = (7.854, 8.004, 8.284), stdev = 0.243
  CI (99.9%): [3.573, 12.435] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.148 ops/ms
# Warmup Iteration   2: 5.902 ops/ms
# Warmup Iteration   3: 6.618 ops/ms
Iteration   1: 6.455 ops/ms
Iteration   2: 6.568 ops/ms
Iteration   3: 6.636 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.553 ±(99.9%) 1.661 ops/ms [Average]
  (min, avg, max) = (6.455, 6.553, 6.636), stdev = 0.091
  CI (99.9%): [4.892, 8.214] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 12.327 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 4.944 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.498 ±(99.9%) 0.004 ms/op
Iteration   1: 4.077 ±(99.9%) 0.006 ms/op
Iteration   2: 3.986 ±(99.9%) 0.003 ms/op
Iteration   3: 4.026 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.030 ±(99.9%) 0.831 ms/op [Average]
  (min, avg, max) = (3.986, 4.030, 4.077), stdev = 0.046
  CI (99.9%): [3.199, 4.860] (assumes normal distribution)


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
# Warmup Iteration   1: 12.908 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.411 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.828 ±(99.9%) 0.003 ms/op
Iteration   1: 3.834 ±(99.9%) 0.004 ms/op
Iteration   2: 3.829 ±(99.9%) 0.004 ms/op
Iteration   3: 3.788 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.817 ±(99.9%) 0.462 ms/op [Average]
  (min, avg, max) = (3.788, 3.817, 3.834), stdev = 0.025
  CI (99.9%): [3.355, 4.279] (assumes normal distribution)


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
# Warmup Iteration   1: 12.301 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.420 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.195 ±(99.9%) 0.003 ms/op
Iteration   1: 4.082 ±(99.9%) 0.004 ms/op
Iteration   2: 4.071 ±(99.9%) 0.004 ms/op
Iteration   3: 3.945 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.033 ±(99.9%) 1.386 ms/op [Average]
  (min, avg, max) = (3.945, 4.033, 4.082), stdev = 0.076
  CI (99.9%): [2.646, 5.419] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 15.293 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 5.319 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.813 ±(99.9%) 0.007 ms/op
Iteration   1: 4.817 ±(99.9%) 0.006 ms/op
Iteration   2: 4.705 ±(99.9%) 0.005 ms/op
Iteration   3: 4.788 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.770 ±(99.9%) 1.068 ms/op [Average]
  (min, avg, max) = (4.705, 4.770, 4.817), stdev = 0.059
  CI (99.9%): [3.702, 5.838] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 12.283 ±(99.9%) 0.174 ms/op
# Warmup Iteration   2: 4.950 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.372 ±(99.9%) 0.017 ms/op
Iteration   1: 4.104 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.792 ms/op
                 createUser·p0.50:   3.908 ms/op
                 createUser·p0.90:   4.735 ms/op
                 createUser·p0.95:   5.325 ms/op
                 createUser·p0.99:   7.873 ms/op
                 createUser·p0.999:  10.898 ms/op
                 createUser·p0.9999: 25.769 ms/op
                 createUser·p1.00:   26.313 ms/op

Iteration   2: 4.082 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.339 ms/op
                 createUser·p0.50:   3.924 ms/op
                 createUser·p0.90:   4.669 ms/op
                 createUser·p0.95:   5.038 ms/op
                 createUser·p0.99:   7.987 ms/op
                 createUser·p0.999:  23.724 ms/op
                 createUser·p0.9999: 27.918 ms/op
                 createUser·p1.00:   30.704 ms/op

Iteration   3: 4.073 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.667 ms/op
                 createUser·p0.50:   3.883 ms/op
                 createUser·p0.90:   4.669 ms/op
                 createUser·p0.95:   5.104 ms/op
                 createUser·p0.99:   7.520 ms/op
                 createUser·p0.999:  21.234 ms/op
                 createUser·p0.9999: 29.933 ms/op
                 createUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 234663
  mean =      4.086 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 417 
    [ 2.500,  5.000) = 220269 
    [ 5.000,  7.500) = 10889 
    [ 7.500, 10.000) = 2377 
    [10.000, 12.500) = 283 
    [12.500, 15.000) = 118 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 122 
    [25.000, 27.500) = 61 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.339 ms/op
     p(50.0000) =      3.908 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.128 ms/op
     p(99.0000) =      7.864 ms/op
     p(99.9000) =     22.162 ms/op
     p(99.9900) =     29.035 ms/op
     p(99.9990) =     31.389 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 12.849 ±(99.9%) 0.199 ms/op
# Warmup Iteration   2: 4.489 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.988 ±(99.9%) 0.012 ms/op
Iteration   1: 3.893 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.634 ms/op
                 existUser·p0.50:   3.740 ms/op
                 existUser·p0.90:   4.293 ms/op
                 existUser·p0.95:   4.784 ms/op
                 existUser·p0.99:   7.799 ms/op
                 existUser·p0.999:  24.177 ms/op
                 existUser·p0.9999: 28.567 ms/op
                 existUser·p1.00:   29.000 ms/op

Iteration   2: 4.033 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.593 ms/op
                 existUser·p0.50:   3.875 ms/op
                 existUser·p0.90:   4.661 ms/op
                 existUser·p0.95:   5.226 ms/op
                 existUser·p0.99:   8.020 ms/op
                 existUser·p0.999:  10.530 ms/op
                 existUser·p0.9999: 27.069 ms/op
                 existUser·p1.00:   28.049 ms/op

Iteration   3: 3.885 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.556 ms/op
                 existUser·p0.50:   3.727 ms/op
                 existUser·p0.90:   4.276 ms/op
                 existUser·p0.95:   4.719 ms/op
                 existUser·p0.99:   8.438 ms/op
                 existUser·p0.999:  16.188 ms/op
                 existUser·p0.9999: 27.787 ms/op
                 existUser·p1.00:   29.065 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 243781
  mean =      3.936 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 421 
    [ 2.500,  5.000) = 231993 
    [ 5.000,  7.500) = 7975 
    [ 7.500, 10.000) = 2461 
    [10.000, 12.500) = 463 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 135 

  Percentiles, ms/op:
      p(0.0000) =      1.556 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.415 ms/op
     p(95.0000) =      4.932 ms/op
     p(99.0000) =      7.995 ms/op
     p(99.9000) =     16.367 ms/op
     p(99.9900) =     27.840 ms/op
     p(99.9990) =     28.985 ms/op
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
# Warmup Iteration   1: 12.011 ±(99.9%) 0.191 ms/op
# Warmup Iteration   2: 4.452 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.065 ±(99.9%) 0.012 ms/op
Iteration   1: 4.161 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.931 ms/op
                 getUser·p0.50:   3.928 ms/op
                 getUser·p0.90:   4.776 ms/op
                 getUser·p0.95:   5.628 ms/op
                 getUser·p0.99:   8.405 ms/op
                 getUser·p0.999:  11.715 ms/op
                 getUser·p0.9999: 30.688 ms/op
                 getUser·p1.00:   33.620 ms/op

Iteration   2: 4.144 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.030 ms/op
                 getUser·p0.50:   3.990 ms/op
                 getUser·p0.90:   4.604 ms/op
                 getUser·p0.95:   5.014 ms/op
                 getUser·p0.99:   7.883 ms/op
                 getUser·p0.999:  15.691 ms/op
                 getUser·p0.9999: 27.010 ms/op
                 getUser·p1.00:   28.017 ms/op

Iteration   3: 4.113 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.898 ms/op
                 getUser·p0.50:   3.973 ms/op
                 getUser·p0.90:   4.620 ms/op
                 getUser·p0.95:   4.882 ms/op
                 getUser·p0.99:   6.717 ms/op
                 getUser·p0.999:  27.207 ms/op
                 getUser·p0.9999: 30.792 ms/op
                 getUser·p1.00:   31.392 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 231927
  mean =      4.139 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 64 
    [ 2.500,  5.000) = 219209 
    [ 5.000,  7.500) = 9264 
    [ 7.500, 10.000) = 2689 
    [10.000, 12.500) = 384 
    [12.500, 15.000) = 44 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 85 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.898 ms/op
     p(50.0000) =      3.961 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.087 ms/op
     p(99.0000) =      8.135 ms/op
     p(99.9000) =     17.337 ms/op
     p(99.9900) =     30.566 ms/op
     p(99.9990) =     32.652 ms/op
     p(99.9999) =     33.620 ms/op
    p(100.0000) =     33.620 ms/op


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
# Warmup Iteration   1: 14.768 ±(99.9%) 0.215 ms/op
# Warmup Iteration   2: 5.398 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.975 ±(99.9%) 0.016 ms/op
Iteration   1: 5.003 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.892 ms/op
                 listUser·p0.50:   4.801 ms/op
                 listUser·p0.90:   5.562 ms/op
                 listUser·p0.95:   6.177 ms/op
                 listUser·p0.99:   9.306 ms/op
                 listUser·p0.999:  24.543 ms/op
                 listUser·p0.9999: 29.366 ms/op
                 listUser·p1.00:   30.999 ms/op

Iteration   2: 5.029 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.874 ms/op
                 listUser·p0.50:   4.899 ms/op
                 listUser·p0.90:   5.497 ms/op
                 listUser·p0.95:   6.013 ms/op
                 listUser·p0.99:   8.815 ms/op
                 listUser·p0.999:  16.446 ms/op
                 listUser·p0.9999: 21.865 ms/op
                 listUser·p1.00:   22.905 ms/op

Iteration   3: 4.886 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.621 ms/op
                 listUser·p0.50:   4.784 ms/op
                 listUser·p0.90:   5.267 ms/op
                 listUser·p0.95:   5.546 ms/op
                 listUser·p0.99:   9.142 ms/op
                 listUser·p0.999:  16.393 ms/op
                 listUser·p0.9999: 17.722 ms/op
                 listUser·p1.00:   19.333 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 193081
  mean =      4.972 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 129849 
    [ 5.000,  7.500) = 58250 
    [ 7.500, 10.000) = 3508 
    [10.000, 12.500) = 641 
    [12.500, 15.000) = 315 
    [15.000, 17.500) = 291 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.874 ms/op
     p(50.0000) =      4.825 ms/op
     p(90.0000) =      5.454 ms/op
     p(95.0000) =      5.906 ms/op
     p(99.0000) =      9.159 ms/op
     p(99.9000) =     18.468 ms/op
     p(99.9900) =     28.443 ms/op
     p(99.9990) =     29.717 ms/op
     p(99.9999) =     30.999 ms/op
    p(100.0000) =     30.999 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.791 ± 4.769  ops/ms
ClientPb.existUser                       thrpt       3   8.225 ± 2.539  ops/ms
ClientPb.getUser                         thrpt       3   8.004 ± 4.431  ops/ms
ClientPb.listUser                        thrpt       3   6.553 ± 1.661  ops/ms
ClientPb.createUser                       avgt       3   4.030 ± 0.831   ms/op
ClientPb.existUser                        avgt       3   3.817 ± 0.462   ms/op
ClientPb.getUser                          avgt       3   4.033 ± 1.386   ms/op
ClientPb.listUser                         avgt       3   4.770 ± 1.068   ms/op
ClientPb.createUser                     sample  234663   4.086 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.339           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.908           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.694           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.128           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.864           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.162           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.035           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.752           ms/op
ClientPb.existUser                      sample  243781   3.936 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.556           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.793           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.415           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.932           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.995           ms/op
ClientPb.existUser:existUser·p0.999     sample          16.367           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.840           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.065           ms/op
ClientPb.getUser                        sample  231927   4.139 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.898           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.961           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.653           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.087           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.135           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.337           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.566           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.620           ms/op
ClientPb.listUser                       sample  193081   4.972 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.874           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.825           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.454           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.906           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.159           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.468           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.443           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.999           ms/op
