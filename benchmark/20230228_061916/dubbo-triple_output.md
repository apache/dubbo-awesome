# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.030 ops/ms
# Warmup Iteration   2: 2.290 ops/ms
# Warmup Iteration   3: 4.605 ops/ms
Iteration   1: 5.724 ops/ms
Iteration   2: 6.093 ops/ms
Iteration   3: 6.194 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.004 ±(99.9%) 4.513 ops/ms [Average]
  (min, avg, max) = (5.724, 6.004, 6.194), stdev = 0.247
  CI (99.9%): [1.490, 10.517] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.572 ops/ms
# Warmup Iteration   2: 5.055 ops/ms
# Warmup Iteration   3: 6.139 ops/ms
Iteration   1: 6.339 ops/ms
Iteration   2: 6.423 ops/ms
Iteration   3: 6.447 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.403 ±(99.9%) 1.033 ops/ms [Average]
  (min, avg, max) = (6.339, 6.403, 6.447), stdev = 0.057
  CI (99.9%): [5.370, 7.436] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.669 ops/ms
# Warmup Iteration   2: 4.208 ops/ms
# Warmup Iteration   3: 5.981 ops/ms
Iteration   1: 5.997 ops/ms
Iteration   2: 6.060 ops/ms
Iteration   3: 6.130 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.063 ±(99.9%) 1.212 ops/ms [Average]
  (min, avg, max) = (5.997, 6.063, 6.130), stdev = 0.066
  CI (99.9%): [4.850, 7.275] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.541 ops/ms
# Warmup Iteration   2: 4.547 ops/ms
# Warmup Iteration   3: 5.166 ops/ms
Iteration   1: 5.200 ops/ms
Iteration   2: 5.294 ops/ms
Iteration   3: 5.188 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.227 ±(99.9%) 1.059 ops/ms [Average]
  (min, avg, max) = (5.188, 5.227, 5.294), stdev = 0.058
  CI (99.9%): [4.168, 6.287] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 19.458 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 6.700 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.558 ±(99.9%) 0.010 ms/op
Iteration   1: 5.270 ±(99.9%) 0.015 ms/op
Iteration   2: 5.364 ±(99.9%) 0.011 ms/op
Iteration   3: 5.307 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.313 ±(99.9%) 0.861 ms/op [Average]
  (min, avg, max) = (5.270, 5.313, 5.364), stdev = 0.047
  CI (99.9%): [4.453, 6.174] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 16.635 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 5.524 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.227 ±(99.9%) 0.009 ms/op
Iteration   1: 4.878 ±(99.9%) 0.017 ms/op
Iteration   2: 5.014 ±(99.9%) 0.011 ms/op
Iteration   3: 4.911 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.934 ±(99.9%) 1.294 ms/op [Average]
  (min, avg, max) = (4.878, 4.934, 5.014), stdev = 0.071
  CI (99.9%): [3.641, 6.228] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 18.612 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 6.804 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.328 ±(99.9%) 0.008 ms/op
Iteration   1: 5.198 ±(99.9%) 0.012 ms/op
Iteration   2: 5.268 ±(99.9%) 0.016 ms/op
Iteration   3: 5.131 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.199 ±(99.9%) 1.250 ms/op [Average]
  (min, avg, max) = (5.131, 5.199, 5.268), stdev = 0.069
  CI (99.9%): [3.949, 6.450] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 18.884 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 7.032 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 6.209 ±(99.9%) 0.011 ms/op
Iteration   1: 6.065 ±(99.9%) 0.013 ms/op
Iteration   2: 6.098 ±(99.9%) 0.014 ms/op
Iteration   3: 6.055 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.073 ±(99.9%) 0.413 ms/op [Average]
  (min, avg, max) = (6.055, 6.073, 6.098), stdev = 0.023
  CI (99.9%): [5.660, 6.486] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 17.265 ±(99.9%) 0.266 ms/op
# Warmup Iteration   2: 6.798 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.603 ±(99.9%) 0.021 ms/op
Iteration   1: 5.554 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.728 ms/op
                 createUser·p0.50:   5.235 ms/op
                 createUser·p0.90:   6.963 ms/op
                 createUser·p0.95:   7.979 ms/op
                 createUser·p0.99:   10.191 ms/op
                 createUser·p0.999:  24.183 ms/op
                 createUser·p0.9999: 26.124 ms/op
                 createUser·p1.00:   27.296 ms/op

Iteration   2: 5.354 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.572 ms/op
                 createUser·p0.50:   5.079 ms/op
                 createUser·p0.90:   6.488 ms/op
                 createUser·p0.95:   7.201 ms/op
                 createUser·p0.99:   10.486 ms/op
                 createUser·p0.999:  23.774 ms/op
                 createUser·p0.9999: 33.778 ms/op
                 createUser·p1.00:   38.404 ms/op

Iteration   3: 5.459 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.666 ms/op
                 createUser·p0.50:   5.145 ms/op
                 createUser·p0.90:   6.644 ms/op
                 createUser·p0.95:   7.709 ms/op
                 createUser·p0.99:   10.600 ms/op
                 createUser·p0.999:  31.076 ms/op
                 createUser·p0.9999: 34.931 ms/op
                 createUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 175853
  mean =      5.454 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 0 
    [ 2.500,  5.000) = 63415 
    [ 5.000,  7.500) = 102583 
    [ 7.500, 10.000) = 7601 
    [10.000, 12.500) = 1443 
    [12.500, 15.000) = 454 
    [15.000, 17.500) = 119 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 15 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 45 
    [35.000, 37.500) = 7 

  Percentiles, ms/op:
      p(0.0000) =      2.572 ms/op
     p(50.0000) =      5.145 ms/op
     p(90.0000) =      6.693 ms/op
     p(95.0000) =      7.684 ms/op
     p(99.0000) =     10.428 ms/op
     p(99.9000) =     24.248 ms/op
     p(99.9900) =     33.778 ms/op
     p(99.9990) =     37.609 ms/op
     p(99.9999) =     38.404 ms/op
    p(100.0000) =     38.404 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 17.828 ±(99.9%) 0.257 ms/op
# Warmup Iteration   2: 5.921 ±(99.9%) 0.034 ms/op
# Warmup Iteration   3: 5.187 ±(99.9%) 0.018 ms/op
Iteration   1: 5.081 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.331 ms/op
                 existUser·p0.50:   4.923 ms/op
                 existUser·p0.90:   5.906 ms/op
                 existUser·p0.95:   6.808 ms/op
                 existUser·p0.99:   9.579 ms/op
                 existUser·p0.999:  21.672 ms/op
                 existUser·p0.9999: 28.032 ms/op
                 existUser·p1.00:   29.524 ms/op

Iteration   2: 5.077 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.458 ms/op
                 existUser·p0.50:   4.825 ms/op
                 existUser·p0.90:   5.956 ms/op
                 existUser·p0.95:   6.922 ms/op
                 existUser·p0.99:   9.667 ms/op
                 existUser·p0.999:  23.887 ms/op
                 existUser·p0.9999: 33.030 ms/op
                 existUser·p1.00:   34.079 ms/op

Iteration   3: 5.045 ±(99.9%) 0.016 ms/op
                 existUser·p0.00:   2.236 ms/op
                 existUser·p0.50:   4.825 ms/op
                 existUser·p0.90:   5.874 ms/op
                 existUser·p0.95:   6.611 ms/op
                 existUser·p0.99:   9.880 ms/op
                 existUser·p0.999:  18.051 ms/op
                 existUser·p0.9999: 28.442 ms/op
                 existUser·p1.00:   29.753 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 189335
  mean =      5.068 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 115855 
    [ 5.000,  7.500) = 67156 
    [ 7.500, 10.000) = 4658 
    [10.000, 12.500) = 1015 
    [12.500, 15.000) = 384 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 72 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.236 ms/op
     p(50.0000) =      4.858 ms/op
     p(90.0000) =      5.915 ms/op
     p(95.0000) =      6.775 ms/op
     p(99.0000) =      9.716 ms/op
     p(99.9000) =     18.806 ms/op
     p(99.9900) =     32.410 ms/op
     p(99.9990) =     33.845 ms/op
     p(99.9999) =     34.079 ms/op
    p(100.0000) =     34.079 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 19.173 ±(99.9%) 0.302 ms/op
# Warmup Iteration   2: 6.568 ±(99.9%) 0.043 ms/op
# Warmup Iteration   3: 5.304 ±(99.9%) 0.018 ms/op
Iteration   1: 5.188 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   1.583 ms/op
                 getUser·p0.50:   4.874 ms/op
                 getUser·p0.90:   6.382 ms/op
                 getUser·p0.95:   7.340 ms/op
                 getUser·p0.99:   10.060 ms/op
                 getUser·p0.999:  21.025 ms/op
                 getUser·p0.9999: 25.756 ms/op
                 getUser·p1.00:   27.001 ms/op

Iteration   2: 5.331 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.531 ms/op
                 getUser·p0.50:   5.005 ms/op
                 getUser·p0.90:   6.406 ms/op
                 getUser·p0.95:   7.676 ms/op
                 getUser·p0.99:   12.339 ms/op
                 getUser·p0.999:  23.898 ms/op
                 getUser·p0.9999: 27.494 ms/op
                 getUser·p1.00:   28.246 ms/op

Iteration   3: 5.284 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.343 ms/op
                 getUser·p0.50:   4.940 ms/op
                 getUser·p0.90:   6.455 ms/op
                 getUser·p0.95:   7.578 ms/op
                 getUser·p0.99:   10.158 ms/op
                 getUser·p0.999:  26.189 ms/op
                 getUser·p0.9999: 30.372 ms/op
                 getUser·p1.00:   31.097 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 182130
  mean =      5.267 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 99045 
    [ 5.000,  7.500) = 73984 
    [ 7.500, 10.000) = 6705 
    [10.000, 12.500) = 1253 
    [12.500, 15.000) = 655 
    [15.000, 17.500) = 154 
    [17.500, 20.000) = 96 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 81 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.583 ms/op
     p(50.0000) =      4.932 ms/op
     p(90.0000) =      6.414 ms/op
     p(95.0000) =      7.496 ms/op
     p(99.0000) =     10.682 ms/op
     p(99.9000) =     23.445 ms/op
     p(99.9900) =     29.295 ms/op
     p(99.9990) =     30.855 ms/op
     p(99.9999) =     31.097 ms/op
    p(100.0000) =     31.097 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 19.087 ±(99.9%) 0.290 ms/op
# Warmup Iteration   2: 7.585 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 6.184 ±(99.9%) 0.025 ms/op
Iteration   1: 6.077 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   0.601 ms/op
                 listUser·p0.50:   5.710 ms/op
                 listUser·p0.90:   7.258 ms/op
                 listUser·p0.95:   8.339 ms/op
                 listUser·p0.99:   11.321 ms/op
                 listUser·p0.999:  27.960 ms/op
                 listUser·p0.9999: 30.531 ms/op
                 listUser·p1.00:   33.194 ms/op

Iteration   2: 6.274 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   3.117 ms/op
                 listUser·p0.50:   5.956 ms/op
                 listUser·p0.90:   7.512 ms/op
                 listUser·p0.95:   8.684 ms/op
                 listUser·p0.99:   12.075 ms/op
                 listUser·p0.999:  27.423 ms/op
                 listUser·p0.9999: 30.680 ms/op
                 listUser·p1.00:   31.621 ms/op

Iteration   3: 5.953 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.605 ms/op
                 listUser·p0.50:   5.661 ms/op
                 listUser·p0.90:   6.971 ms/op
                 listUser·p0.95:   8.012 ms/op
                 listUser·p0.99:   10.617 ms/op
                 listUser·p0.999:  21.725 ms/op
                 listUser·p0.9999: 24.723 ms/op
                 listUser·p1.00:   25.166 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 157447
  mean =      6.098 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 9448 
    [ 5.000,  7.500) = 134770 
    [ 7.500, 10.000) = 10107 
    [10.000, 12.500) = 2206 
    [12.500, 15.000) = 430 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 81 
    [22.500, 25.000) = 78 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 81 
    [30.000, 32.500) = 19 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.601 ms/op
     p(50.0000) =      5.775 ms/op
     p(90.0000) =      7.242 ms/op
     p(95.0000) =      8.372 ms/op
     p(99.0000) =     11.338 ms/op
     p(99.9000) =     25.100 ms/op
     p(99.9900) =     30.319 ms/op
     p(99.9990) =     33.175 ms/op
     p(99.9999) =     33.194 ms/op
    p(100.0000) =     33.194 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.004 ± 4.513  ops/ms
ClientPb.existUser                       thrpt       3   6.403 ± 1.033  ops/ms
ClientPb.getUser                         thrpt       3   6.063 ± 1.212  ops/ms
ClientPb.listUser                        thrpt       3   5.227 ± 1.059  ops/ms
ClientPb.createUser                       avgt       3   5.313 ± 0.861   ms/op
ClientPb.existUser                        avgt       3   4.934 ± 1.294   ms/op
ClientPb.getUser                          avgt       3   5.199 ± 1.250   ms/op
ClientPb.listUser                         avgt       3   6.073 ± 0.413   ms/op
ClientPb.createUser                     sample  175853   5.454 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.572           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.145           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.693           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.684           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.428           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.248           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.778           ms/op
ClientPb.createUser:createUser·p1.00    sample          38.404           ms/op
ClientPb.existUser                      sample  189335   5.068 ± 0.009   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.236           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.858           ms/op
ClientPb.existUser:existUser·p0.90      sample           5.915           ms/op
ClientPb.existUser:existUser·p0.95      sample           6.775           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.716           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.806           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.410           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.079           ms/op
ClientPb.getUser                        sample  182130   5.267 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.583           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.932           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.414           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.496           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.682           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.445           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.295           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.097           ms/op
ClientPb.listUser                       sample  157447   6.098 ± 0.012   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.601           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.775           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.242           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.372           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.338           ms/op
ClientPb.listUser:listUser·p0.999       sample          25.100           ms/op
ClientPb.listUser:listUser·p0.9999      sample          30.319           ms/op
ClientPb.listUser:listUser·p1.00        sample          33.194           ms/op
