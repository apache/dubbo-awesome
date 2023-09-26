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
# Warmup Iteration   1: 1.638 ops/ms
# Warmup Iteration   2: 3.463 ops/ms
# Warmup Iteration   3: 7.334 ops/ms
Iteration   1: 7.586 ops/ms
Iteration   2: 8.039 ops/ms
Iteration   3: 8.029 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.885 ±(99.9%) 4.719 ops/ms [Average]
  (min, avg, max) = (7.586, 7.885, 8.039), stdev = 0.259
  CI (99.9%): [3.166, 12.603] (assumes normal distribution)


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
# Warmup Iteration   1: 2.204 ops/ms
# Warmup Iteration   2: 7.187 ops/ms
# Warmup Iteration   3: 8.416 ops/ms
Iteration   1: 8.423 ops/ms
Iteration   2: 8.514 ops/ms
Iteration   3: 8.581 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.506 ±(99.9%) 1.453 ops/ms [Average]
  (min, avg, max) = (8.423, 8.506, 8.581), stdev = 0.080
  CI (99.9%): [7.053, 9.959] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 2.188 ops/ms
# Warmup Iteration   2: 6.389 ops/ms
# Warmup Iteration   3: 7.810 ops/ms
Iteration   1: 8.026 ops/ms
Iteration   2: 8.114 ops/ms
Iteration   3: 8.149 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.096 ±(99.9%) 1.151 ops/ms [Average]
  (min, avg, max) = (8.026, 8.096, 8.149), stdev = 0.063
  CI (99.9%): [6.946, 9.247] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.105 ops/ms
# Warmup Iteration   2: 5.247 ops/ms
# Warmup Iteration   3: 6.710 ops/ms
Iteration   1: 6.690 ops/ms
Iteration   2: 6.601 ops/ms
Iteration   3: 6.723 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.671 ±(99.9%) 1.156 ops/ms [Average]
  (min, avg, max) = (6.601, 6.671, 6.723), stdev = 0.063
  CI (99.9%): [5.516, 7.827] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 13.603 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.394 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.243 ±(99.9%) 0.004 ms/op
Iteration   1: 4.214 ±(99.9%) 0.007 ms/op
Iteration   2: 3.998 ±(99.9%) 0.004 ms/op
Iteration   3: 3.971 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.061 ±(99.9%) 2.429 ms/op [Average]
  (min, avg, max) = (3.971, 4.061, 4.214), stdev = 0.133
  CI (99.9%): [1.632, 6.490] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 11.533 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.337 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.738 ±(99.9%) 0.009 ms/op
Iteration   1: 3.837 ±(99.9%) 0.007 ms/op
Iteration   2: 3.789 ±(99.9%) 0.004 ms/op
Iteration   3: 3.901 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.842 ±(99.9%) 1.029 ms/op [Average]
  (min, avg, max) = (3.789, 3.842, 3.901), stdev = 0.056
  CI (99.9%): [2.813, 4.871] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 12.860 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.350 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.943 ±(99.9%) 0.004 ms/op
Iteration   1: 4.057 ±(99.9%) 0.004 ms/op
Iteration   2: 3.924 ±(99.9%) 0.004 ms/op
Iteration   3: 3.866 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.949 ±(99.9%) 1.782 ms/op [Average]
  (min, avg, max) = (3.866, 3.949, 4.057), stdev = 0.098
  CI (99.9%): [2.167, 5.731] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 13.264 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.481 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.857 ±(99.9%) 0.007 ms/op
Iteration   1: 4.769 ±(99.9%) 0.007 ms/op
Iteration   2: 4.720 ±(99.9%) 0.007 ms/op
Iteration   3: 4.705 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.731 ±(99.9%) 0.611 ms/op [Average]
  (min, avg, max) = (4.705, 4.731, 4.769), stdev = 0.034
  CI (99.9%): [4.120, 5.343] (assumes normal distribution)


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
# Warmup Iteration   1: 13.448 ±(99.9%) 0.171 ms/op
# Warmup Iteration   2: 4.793 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.342 ±(99.9%) 0.016 ms/op
Iteration   1: 4.090 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.948 ms/op
                 createUser·p0.50:   3.949 ms/op
                 createUser·p0.90:   4.678 ms/op
                 createUser·p0.95:   4.989 ms/op
                 createUser·p0.99:   7.643 ms/op
                 createUser·p0.999:  24.373 ms/op
                 createUser·p0.9999: 27.072 ms/op
                 createUser·p1.00:   27.623 ms/op

Iteration   2: 3.945 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.382 ms/op
                 createUser·p0.50:   3.846 ms/op
                 createUser·p0.90:   4.440 ms/op
                 createUser·p0.95:   4.768 ms/op
                 createUser·p0.99:   6.655 ms/op
                 createUser·p0.999:  13.889 ms/op
                 createUser·p0.9999: 27.591 ms/op
                 createUser·p1.00:   28.574 ms/op

Iteration   3: 4.050 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.327 ms/op
                 createUser·p0.50:   3.871 ms/op
                 createUser·p0.90:   4.612 ms/op
                 createUser·p0.95:   4.964 ms/op
                 createUser·p0.99:   6.767 ms/op
                 createUser·p0.999:  28.444 ms/op
                 createUser·p0.9999: 31.002 ms/op
                 createUser·p1.00:   31.228 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 238324
  mean =      4.027 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 344 
    [ 2.500,  5.000) = 227728 
    [ 5.000,  7.500) = 8370 
    [ 7.500, 10.000) = 1115 
    [10.000, 12.500) = 389 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 56 
    [25.000, 27.500) = 89 
    [27.500, 30.000) = 79 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.327 ms/op
     p(50.0000) =      3.887 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      6.955 ms/op
     p(99.9000) =     24.369 ms/op
     p(99.9900) =     30.414 ms/op
     p(99.9990) =     31.183 ms/op
     p(99.9999) =     31.228 ms/op
    p(100.0000) =     31.228 ms/op


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
# Warmup Iteration   1: 12.248 ±(99.9%) 0.181 ms/op
# Warmup Iteration   2: 4.310 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.977 ±(99.9%) 0.012 ms/op
Iteration   1: 3.928 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.548 ms/op
                 existUser·p0.50:   3.797 ms/op
                 existUser·p0.90:   4.514 ms/op
                 existUser·p0.95:   4.915 ms/op
                 existUser·p0.99:   7.250 ms/op
                 existUser·p0.999:  18.485 ms/op
                 existUser·p0.9999: 26.079 ms/op
                 existUser·p1.00:   26.968 ms/op

Iteration   2: 3.875 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.855 ms/op
                 existUser·p0.50:   3.731 ms/op
                 existUser·p0.90:   4.284 ms/op
                 existUser·p0.95:   4.735 ms/op
                 existUser·p0.99:   7.029 ms/op
                 existUser·p0.999:  25.017 ms/op
                 existUser·p0.9999: 28.057 ms/op
                 existUser·p1.00:   29.065 ms/op

Iteration   3: 3.945 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.534 ms/op
                 existUser·p0.50:   3.764 ms/op
                 existUser·p0.90:   4.538 ms/op
                 existUser·p0.95:   4.874 ms/op
                 existUser·p0.99:   7.021 ms/op
                 existUser·p0.999:  11.272 ms/op
                 existUser·p0.9999: 29.583 ms/op
                 existUser·p1.00:   30.573 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 245016
  mean =      3.916 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 244 
    [ 2.500,  5.000) = 234751 
    [ 5.000,  7.500) = 8097 
    [ 7.500, 10.000) = 1348 
    [10.000, 12.500) = 252 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 106 
    [27.500, 30.000) = 61 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.534 ms/op
     p(50.0000) =      3.768 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      4.858 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     18.415 ms/op
     p(99.9900) =     28.475 ms/op
     p(99.9990) =     30.463 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


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
# Warmup Iteration   1: 12.128 ±(99.9%) 0.179 ms/op
# Warmup Iteration   2: 4.490 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.055 ±(99.9%) 0.011 ms/op
Iteration   1: 4.066 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.710 ms/op
                 getUser·p0.50:   3.801 ms/op
                 getUser·p0.90:   4.440 ms/op
                 getUser·p0.95:   6.218 ms/op
                 getUser·p0.99:   8.602 ms/op
                 getUser·p0.999:  21.506 ms/op
                 getUser·p0.9999: 23.857 ms/op
                 getUser·p1.00:   25.100 ms/op

Iteration   2: 3.943 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.757 ms/op
                 getUser·p0.50:   3.834 ms/op
                 getUser·p0.90:   4.342 ms/op
                 getUser·p0.95:   4.628 ms/op
                 getUser·p0.99:   7.004 ms/op
                 getUser·p0.999:  12.911 ms/op
                 getUser·p0.9999: 26.235 ms/op
                 getUser·p1.00:   26.903 ms/op

Iteration   3: 4.072 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.690 ms/op
                 getUser·p0.50:   3.920 ms/op
                 getUser·p0.90:   4.489 ms/op
                 getUser·p0.95:   4.932 ms/op
                 getUser·p0.99:   8.184 ms/op
                 getUser·p0.999:  11.209 ms/op
                 getUser·p0.9999: 26.153 ms/op
                 getUser·p1.00:   27.099 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 238516
  mean =      4.026 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 102 
    [ 2.500,  5.000) = 226728 
    [ 5.000,  7.500) = 7452 
    [ 7.500, 10.000) = 3370 
    [10.000, 12.500) = 489 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 51 
    [22.500, 25.000) = 114 
    [25.000, 27.500) = 63 

  Percentiles, ms/op:
      p(0.0000) =      1.690 ms/op
     p(50.0000) =      3.850 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.964 ms/op
     p(99.0000) =      8.109 ms/op
     p(99.9000) =     19.118 ms/op
     p(99.9900) =     26.018 ms/op
     p(99.9990) =     27.034 ms/op
     p(99.9999) =     27.099 ms/op
    p(100.0000) =     27.099 ms/op


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
# Warmup Iteration   1: 15.766 ±(99.9%) 0.225 ms/op
# Warmup Iteration   2: 5.895 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 4.962 ±(99.9%) 0.016 ms/op
Iteration   1: 4.850 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.935 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   5.407 ms/op
                 listUser·p0.95:   5.767 ms/op
                 listUser·p0.99:   8.536 ms/op
                 listUser·p0.999:  26.247 ms/op
                 listUser·p0.9999: 28.423 ms/op
                 listUser·p1.00:   28.606 ms/op

Iteration   2: 4.777 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.622 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   8.631 ms/op
                 listUser·p0.999:  19.043 ms/op
                 listUser·p0.9999: 24.170 ms/op
                 listUser·p1.00:   26.214 ms/op

Iteration   3: 4.779 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.343 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   5.243 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   8.372 ms/op
                 listUser·p0.999:  16.007 ms/op
                 listUser·p0.9999: 17.279 ms/op
                 listUser·p1.00:   19.366 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 199762
  mean =      4.802 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 159944 
    [ 5.000,  7.500) = 35855 
    [ 7.500, 10.000) = 3026 
    [10.000, 12.500) = 324 
    [12.500, 15.000) = 170 
    [15.000, 17.500) = 184 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 84 

  Percentiles, ms/op:
      p(0.0000) =      1.622 ms/op
     p(50.0000) =      4.645 ms/op
     p(90.0000) =      5.267 ms/op
     p(95.0000) =      5.685 ms/op
     p(99.0000) =      8.536 ms/op
     p(99.9000) =     19.005 ms/op
     p(99.9900) =     27.854 ms/op
     p(99.9990) =     28.574 ms/op
     p(99.9999) =     28.606 ms/op
    p(100.0000) =     28.606 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.885 ± 4.719  ops/ms
ClientPb.existUser                       thrpt       3   8.506 ± 1.453  ops/ms
ClientPb.getUser                         thrpt       3   8.096 ± 1.151  ops/ms
ClientPb.listUser                        thrpt       3   6.671 ± 1.156  ops/ms
ClientPb.createUser                       avgt       3   4.061 ± 2.429   ms/op
ClientPb.existUser                        avgt       3   3.842 ± 1.029   ms/op
ClientPb.getUser                          avgt       3   3.949 ± 1.782   ms/op
ClientPb.listUser                         avgt       3   4.731 ± 0.611   ms/op
ClientPb.createUser                     sample  238324   4.027 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.327           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.887           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.588           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.923           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.955           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.369           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.414           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.228           ms/op
ClientPb.existUser                      sample  245016   3.916 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.534           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.768           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.465           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.858           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.086           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.415           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.475           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.573           ms/op
ClientPb.getUser                        sample  238516   4.026 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.690           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.850           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.424           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.964           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.109           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.118           ms/op
ClientPb.getUser:getUser·p0.9999        sample          26.018           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.099           ms/op
ClientPb.listUser                       sample  199762   4.802 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.622           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.645           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.267           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.685           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.536           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.005           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.854           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.606           ms/op
