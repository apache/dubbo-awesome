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
# Warmup Iteration   1: 1.498 ops/ms
# Warmup Iteration   2: 4.118 ops/ms
# Warmup Iteration   3: 6.001 ops/ms
Iteration   1: 6.260 ops/ms
Iteration   2: 6.408 ops/ms
Iteration   3: 6.121 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  6.263 ±(99.9%) 2.620 ops/ms [Average]
  (min, avg, max) = (6.121, 6.263, 6.408), stdev = 0.144
  CI (99.9%): [3.643, 8.883] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:10
# Fork: 1 of 1
# Warmup Iteration   1: 1.740 ops/ms
# Warmup Iteration   2: 5.561 ops/ms
# Warmup Iteration   3: 6.507 ops/ms
Iteration   1: 6.405 ops/ms
Iteration   2: 6.489 ops/ms
Iteration   3: 6.232 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.375 ±(99.9%) 2.389 ops/ms [Average]
  (min, avg, max) = (6.232, 6.375, 6.489), stdev = 0.131
  CI (99.9%): [3.986, 8.764] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:59
# Fork: 1 of 1
# Warmup Iteration   1: 1.754 ops/ms
# Warmup Iteration   2: 5.444 ops/ms
# Warmup Iteration   3: 6.195 ops/ms
Iteration   1: 5.993 ops/ms
Iteration   2: 5.561 ops/ms
Iteration   3: 5.947 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.834 ±(99.9%) 4.327 ops/ms [Average]
  (min, avg, max) = (5.561, 5.834, 5.993), stdev = 0.237
  CI (99.9%): [1.507, 10.161] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.585 ops/ms
# Warmup Iteration   2: 3.770 ops/ms
# Warmup Iteration   3: 4.974 ops/ms
Iteration   1: 4.968 ops/ms
Iteration   2: 4.671 ops/ms
Iteration   3: 5.113 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.917 ±(99.9%) 4.112 ops/ms [Average]
  (min, avg, max) = (4.671, 4.917, 5.113), stdev = 0.225
  CI (99.9%): [0.806, 9.029] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 15.526 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 6.170 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.428 ±(99.9%) 0.006 ms/op
Iteration   1: 5.267 ±(99.9%) 0.011 ms/op
Iteration   2: 5.024 ±(99.9%) 0.012 ms/op
Iteration   3: 5.170 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.153 ±(99.9%) 2.233 ms/op [Average]
  (min, avg, max) = (5.024, 5.153, 5.267), stdev = 0.122
  CI (99.9%): [2.920, 7.387] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 15.149 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 5.362 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 5.152 ±(99.9%) 0.007 ms/op
Iteration   1: 4.988 ±(99.9%) 0.010 ms/op
Iteration   2: 5.069 ±(99.9%) 0.016 ms/op
Iteration   3: 4.860 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.972 ±(99.9%) 1.923 ms/op [Average]
  (min, avg, max) = (4.860, 4.972, 5.069), stdev = 0.105
  CI (99.9%): [3.049, 6.895] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 15.438 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 5.957 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.236 ±(99.9%) 0.013 ms/op
Iteration   1: 5.232 ±(99.9%) 0.012 ms/op
Iteration   2: 5.090 ±(99.9%) 0.013 ms/op
Iteration   3: 4.998 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.107 ±(99.9%) 2.149 ms/op [Average]
  (min, avg, max) = (4.998, 5.107, 5.232), stdev = 0.118
  CI (99.9%): [2.957, 7.256] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 17.128 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 7.359 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 6.325 ±(99.9%) 0.009 ms/op
Iteration   1: 6.049 ±(99.9%) 0.015 ms/op
Iteration   2: 5.849 ±(99.9%) 0.016 ms/op
Iteration   3: 5.943 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.947 ±(99.9%) 1.827 ms/op [Average]
  (min, avg, max) = (5.849, 5.947, 6.049), stdev = 0.100
  CI (99.9%): [4.120, 7.774] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 16.792 ±(99.9%) 0.306 ms/op
# Warmup Iteration   2: 6.199 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 5.646 ±(99.9%) 0.024 ms/op
Iteration   1: 5.250 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.208 ms/op
                 createUser·p0.50:   5.063 ms/op
                 createUser·p0.90:   6.431 ms/op
                 createUser·p0.95:   7.012 ms/op
                 createUser·p0.99:   8.782 ms/op
                 createUser·p0.999:  23.189 ms/op
                 createUser·p0.9999: 27.001 ms/op
                 createUser·p1.00:   31.523 ms/op

Iteration   2: 5.395 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.150 ms/op
                 createUser·p0.50:   5.177 ms/op
                 createUser·p0.90:   6.857 ms/op
                 createUser·p0.95:   7.651 ms/op
                 createUser·p0.99:   9.961 ms/op
                 createUser·p0.999:  25.900 ms/op
                 createUser·p0.9999: 32.087 ms/op
                 createUser·p1.00:   32.768 ms/op

Iteration   3: 4.965 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   0.977 ms/op
                 createUser·p0.50:   4.678 ms/op
                 createUser·p0.90:   6.111 ms/op
                 createUser·p0.95:   6.857 ms/op
                 createUser·p0.99:   9.683 ms/op
                 createUser·p0.999:  27.807 ms/op
                 createUser·p0.9999: 31.850 ms/op
                 createUser·p1.00:   33.423 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 184597
  mean =      5.197 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 88 
    [ 2.500,  5.000) = 100020 
    [ 5.000,  7.500) = 76952 
    [ 7.500, 10.000) = 6099 
    [10.000, 12.500) = 957 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 50 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 37 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 73 
    [30.000, 32.500) = 39 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.977 ms/op
     p(50.0000) =      4.899 ms/op
     p(90.0000) =      6.480 ms/op
     p(95.0000) =      7.266 ms/op
     p(99.0000) =      9.601 ms/op
     p(99.9000) =     25.074 ms/op
     p(99.9900) =     31.730 ms/op
     p(99.9990) =     33.423 ms/op
     p(99.9999) =     33.423 ms/op
    p(100.0000) =     33.423 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 16.276 ±(99.9%) 0.269 ms/op
# Warmup Iteration   2: 6.397 ±(99.9%) 0.039 ms/op
# Warmup Iteration   3: 5.384 ±(99.9%) 0.019 ms/op
Iteration   1: 5.343 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.277 ms/op
                 existUser·p0.50:   5.022 ms/op
                 existUser·p0.90:   6.824 ms/op
                 existUser·p0.95:   7.684 ms/op
                 existUser·p0.99:   10.322 ms/op
                 existUser·p0.999:  14.229 ms/op
                 existUser·p0.9999: 29.853 ms/op
                 existUser·p1.00:   31.162 ms/op

Iteration   2: 5.436 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.228 ms/op
                 existUser·p0.50:   5.104 ms/op
                 existUser·p0.90:   6.963 ms/op
                 existUser·p0.95:   7.889 ms/op
                 existUser·p0.99:   10.043 ms/op
                 existUser·p0.999:  25.565 ms/op
                 existUser·p0.9999: 28.867 ms/op
                 existUser·p1.00:   29.491 ms/op

Iteration   3: 5.595 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.343 ms/op
                 existUser·p0.50:   5.267 ms/op
                 existUser·p0.90:   7.078 ms/op
                 existUser·p0.95:   8.110 ms/op
                 existUser·p0.99:   11.693 ms/op
                 existUser·p0.999:  27.680 ms/op
                 existUser·p0.9999: 31.158 ms/op
                 existUser·p1.00:   32.113 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 175883
  mean =      5.456 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 33 
    [ 2.500,  5.000) = 77999 
    [ 5.000,  7.500) = 86406 
    [ 7.500, 10.000) = 9256 
    [10.000, 12.500) = 1318 
    [12.500, 15.000) = 535 
    [15.000, 17.500) = 149 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 69 
    [27.500, 30.000) = 80 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.228 ms/op
     p(50.0000) =      5.128 ms/op
     p(90.0000) =      6.947 ms/op
     p(95.0000) =      7.897 ms/op
     p(99.0000) =     10.521 ms/op
     p(99.9000) =     19.468 ms/op
     p(99.9900) =     30.162 ms/op
     p(99.9990) =     31.914 ms/op
     p(99.9999) =     32.113 ms/op
    p(100.0000) =     32.113 ms/op


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
# Warmup Iteration   1: 18.117 ±(99.9%) 0.323 ms/op
# Warmup Iteration   2: 6.844 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.417 ±(99.9%) 0.022 ms/op
Iteration   1: 5.302 ±(99.9%) 0.018 ms/op
                 getUser·p0.00:   2.249 ms/op
                 getUser·p0.50:   5.079 ms/op
                 getUser·p0.90:   6.357 ms/op
                 getUser·p0.95:   7.135 ms/op
                 getUser·p0.99:   9.748 ms/op
                 getUser·p0.999:  22.782 ms/op
                 getUser·p0.9999: 33.943 ms/op
                 getUser·p1.00:   34.341 ms/op

Iteration   2: 5.194 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   1.866 ms/op
                 getUser·p0.50:   4.891 ms/op
                 getUser·p0.90:   6.341 ms/op
                 getUser·p0.95:   7.340 ms/op
                 getUser·p0.99:   10.715 ms/op
                 getUser·p0.999:  24.260 ms/op
                 getUser·p0.9999: 27.329 ms/op
                 getUser·p1.00:   28.312 ms/op

Iteration   3: 5.493 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.413 ms/op
                 getUser·p0.50:   5.276 ms/op
                 getUser·p0.90:   6.849 ms/op
                 getUser·p0.95:   7.832 ms/op
                 getUser·p0.99:   9.942 ms/op
                 getUser·p0.999:  16.643 ms/op
                 getUser·p0.9999: 36.855 ms/op
                 getUser·p1.00:   37.159 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 180138
  mean =      5.326 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9 
    [ 2.500,  5.000) = 86031 
    [ 5.000,  7.500) = 85257 
    [ 7.500, 10.000) = 6920 
    [10.000, 12.500) = 1191 
    [12.500, 15.000) = 391 
    [15.000, 17.500) = 131 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 30 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 15 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.866 ms/op
     p(50.0000) =      5.046 ms/op
     p(90.0000) =      6.529 ms/op
     p(95.0000) =      7.471 ms/op
     p(99.0000) =     10.125 ms/op
     p(99.9000) =     20.524 ms/op
     p(99.9900) =     35.652 ms/op
     p(99.9990) =     37.159 ms/op
     p(99.9999) =     37.159 ms/op
    p(100.0000) =     37.159 ms/op


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
# Warmup Iteration   1: 17.888 ±(99.9%) 0.283 ms/op
# Warmup Iteration   2: 7.349 ±(99.9%) 0.046 ms/op
# Warmup Iteration   3: 6.406 ±(99.9%) 0.025 ms/op
Iteration   1: 5.986 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.970 ms/op
                 listUser·p0.50:   5.652 ms/op
                 listUser·p0.90:   7.315 ms/op
                 listUser·p0.95:   8.135 ms/op
                 listUser·p0.99:   11.207 ms/op
                 listUser·p0.999:  26.706 ms/op
                 listUser·p0.9999: 29.349 ms/op
                 listUser·p1.00:   30.409 ms/op

Iteration   2: 6.149 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   0.708 ms/op
                 listUser·p0.50:   5.816 ms/op
                 listUser·p0.90:   7.635 ms/op
                 listUser·p0.95:   8.667 ms/op
                 listUser·p0.99:   11.043 ms/op
                 listUser·p0.999:  24.638 ms/op
                 listUser·p0.9999: 29.333 ms/op
                 listUser·p1.00:   30.147 ms/op

Iteration   3: 6.229 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   2.671 ms/op
                 listUser·p0.50:   5.898 ms/op
                 listUser·p0.90:   7.733 ms/op
                 listUser·p0.95:   8.733 ms/op
                 listUser·p0.99:   10.858 ms/op
                 listUser·p0.999:  21.496 ms/op
                 listUser·p0.9999: 23.785 ms/op
                 listUser·p1.00:   24.510 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 156798
  mean =      6.120 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 19436 
    [ 5.000,  7.500) = 120711 
    [ 7.500, 10.000) = 13992 
    [10.000, 12.500) = 1713 
    [12.500, 15.000) = 483 
    [15.000, 17.500) = 114 
    [17.500, 20.000) = 41 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 115 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.708 ms/op
     p(50.0000) =      5.767 ms/op
     p(90.0000) =      7.569 ms/op
     p(95.0000) =      8.536 ms/op
     p(99.0000) =     11.010 ms/op
     p(99.9000) =     24.320 ms/op
     p(99.9900) =     29.010 ms/op
     p(99.9990) =     30.260 ms/op
     p(99.9999) =     30.409 ms/op
    p(100.0000) =     30.409 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   6.263 ± 2.620  ops/ms
ClientPb.existUser                       thrpt       3   6.375 ± 2.389  ops/ms
ClientPb.getUser                         thrpt       3   5.834 ± 4.327  ops/ms
ClientPb.listUser                        thrpt       3   4.917 ± 4.112  ops/ms
ClientPb.createUser                       avgt       3   5.153 ± 2.233   ms/op
ClientPb.existUser                        avgt       3   4.972 ± 1.923   ms/op
ClientPb.getUser                          avgt       3   5.107 ± 2.149   ms/op
ClientPb.listUser                         avgt       3   5.947 ± 1.827   ms/op
ClientPb.createUser                     sample  184597   5.197 ± 0.011   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.977           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.899           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.480           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.266           ms/op
ClientPb.createUser:createUser·p0.99    sample           9.601           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.074           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.730           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.423           ms/op
ClientPb.existUser                      sample  175883   5.456 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.228           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.128           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.947           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.897           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.521           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.468           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.162           ms/op
ClientPb.existUser:existUser·p1.00      sample          32.113           ms/op
ClientPb.getUser                        sample  180138   5.326 ± 0.011   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.866           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.046           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.529           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.471           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.125           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.524           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.652           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.159           ms/op
ClientPb.listUser                       sample  156798   6.120 ± 0.013   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.708           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.767           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.569           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.536           ms/op
ClientPb.listUser:listUser·p0.99        sample          11.010           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.320           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.010           ms/op
ClientPb.listUser:listUser·p1.00        sample          30.409           ms/op
