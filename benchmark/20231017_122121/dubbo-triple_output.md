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
# Warmup Iteration   1: 1.007 ops/ms
# Warmup Iteration   2: 2.409 ops/ms
# Warmup Iteration   3: 5.124 ops/ms
Iteration   1: 5.389 ops/ms
Iteration   2: 5.456 ops/ms
Iteration   3: 5.583 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.476 ±(99.9%) 1.799 ops/ms [Average]
  (min, avg, max) = (5.389, 5.476, 5.583), stdev = 0.099
  CI (99.9%): [3.677, 7.275] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 1.377 ops/ms
# Warmup Iteration   2: 4.193 ops/ms
# Warmup Iteration   3: 5.663 ops/ms
Iteration   1: 5.682 ops/ms
Iteration   2: 5.754 ops/ms
Iteration   3: 5.695 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.710 ±(99.9%) 0.699 ops/ms [Average]
  (min, avg, max) = (5.682, 5.710, 5.754), stdev = 0.038
  CI (99.9%): [5.012, 6.409] (assumes normal distribution)


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
# Warmup Iteration   1: 1.474 ops/ms
# Warmup Iteration   2: 4.213 ops/ms
# Warmup Iteration   3: 5.536 ops/ms
Iteration   1: 5.368 ops/ms
Iteration   2: 5.609 ops/ms
Iteration   3: 5.636 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.538 ±(99.9%) 2.688 ops/ms [Average]
  (min, avg, max) = (5.368, 5.538, 5.636), stdev = 0.147
  CI (99.9%): [2.850, 8.225] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.374 ops/ms
# Warmup Iteration   2: 3.330 ops/ms
# Warmup Iteration   3: 4.481 ops/ms
Iteration   1: 4.597 ops/ms
Iteration   2: 4.722 ops/ms
Iteration   3: 4.660 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.660 ±(99.9%) 1.141 ops/ms [Average]
  (min, avg, max) = (4.597, 4.660, 4.722), stdev = 0.063
  CI (99.9%): [3.518, 5.801] (assumes normal distribution)


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
# Warmup Iteration   1: 19.493 ±(99.9%) 0.187 ms/op
# Warmup Iteration   2: 7.398 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.964 ±(99.9%) 0.011 ms/op
Iteration   1: 5.941 ±(99.9%) 0.010 ms/op
Iteration   2: 5.766 ±(99.9%) 0.011 ms/op
Iteration   3: 5.507 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.738 ±(99.9%) 3.992 ms/op [Average]
  (min, avg, max) = (5.507, 5.738, 5.941), stdev = 0.219
  CI (99.9%): [1.747, 9.730] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 17.365 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 7.041 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.500 ±(99.9%) 0.006 ms/op
Iteration   1: 5.668 ±(99.9%) 0.005 ms/op
Iteration   2: 5.509 ±(99.9%) 0.008 ms/op
Iteration   3: 5.481 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.553 ±(99.9%) 1.847 ms/op [Average]
  (min, avg, max) = (5.481, 5.553, 5.668), stdev = 0.101
  CI (99.9%): [3.705, 7.400] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:40
# Fork: 1 of 1
# Warmup Iteration   1: 18.767 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 6.703 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.806 ±(99.9%) 0.010 ms/op
Iteration   1: 5.743 ±(99.9%) 0.007 ms/op
Iteration   2: 5.588 ±(99.9%) 0.012 ms/op
Iteration   3: 5.427 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.586 ±(99.9%) 2.882 ms/op [Average]
  (min, avg, max) = (5.427, 5.586, 5.743), stdev = 0.158
  CI (99.9%): [2.704, 8.468] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:33
# Fork: 1 of 1
# Warmup Iteration   1: 20.520 ±(99.9%) 0.093 ms/op
# Warmup Iteration   2: 8.459 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.835 ±(99.9%) 0.012 ms/op
Iteration   1: 6.793 ±(99.9%) 0.010 ms/op
Iteration   2: 6.712 ±(99.9%) 0.018 ms/op
Iteration   3: 7.051 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.852 ±(99.9%) 3.228 ms/op [Average]
  (min, avg, max) = (6.712, 6.852, 7.051), stdev = 0.177
  CI (99.9%): [3.624, 10.081] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:27
# Fork: 1 of 1
# Warmup Iteration   1: 19.740 ±(99.9%) 0.313 ms/op
# Warmup Iteration   2: 8.120 ±(99.9%) 0.067 ms/op
# Warmup Iteration   3: 6.322 ±(99.9%) 0.033 ms/op
Iteration   1: 5.553 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.454 ms/op
                 createUser·p0.50:   5.251 ms/op
                 createUser·p0.90:   6.816 ms/op
                 createUser·p0.95:   7.643 ms/op
                 createUser·p0.99:   10.224 ms/op
                 createUser·p0.999:  23.706 ms/op
                 createUser·p0.9999: 27.099 ms/op
                 createUser·p1.00:   27.623 ms/op

Iteration   2: 5.705 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   2.413 ms/op
                 createUser·p0.50:   5.325 ms/op
                 createUser·p0.90:   7.143 ms/op
                 createUser·p0.95:   7.995 ms/op
                 createUser·p0.99:   10.673 ms/op
                 createUser·p0.999:  15.885 ms/op
                 createUser·p0.9999: 30.204 ms/op
                 createUser·p1.00:   30.671 ms/op

Iteration   3: 5.717 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   2.630 ms/op
                 createUser·p0.50:   5.276 ms/op
                 createUser·p0.90:   7.274 ms/op
                 createUser·p0.95:   8.503 ms/op
                 createUser·p0.99:   11.616 ms/op
                 createUser·p0.999:  26.052 ms/op
                 createUser·p0.9999: 30.560 ms/op
                 createUser·p1.00:   32.047 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 169593
  mean =      5.657 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 56965 
    [ 5.000,  7.500) = 100419 
    [ 7.500, 10.000) = 9514 
    [10.000, 12.500) = 1801 
    [12.500, 15.000) = 489 
    [15.000, 17.500) = 196 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.413 ms/op
     p(50.0000) =      5.284 ms/op
     p(90.0000) =      7.062 ms/op
     p(95.0000) =      8.036 ms/op
     p(99.0000) =     10.945 ms/op
     p(99.9000) =     20.414 ms/op
     p(99.9900) =     29.787 ms/op
     p(99.9990) =     32.001 ms/op
     p(99.9999) =     32.047 ms/op
    p(100.0000) =     32.047 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:20
# Fork: 1 of 1
# Warmup Iteration   1: 17.318 ±(99.9%) 0.280 ms/op
# Warmup Iteration   2: 7.845 ±(99.9%) 0.059 ms/op
# Warmup Iteration   3: 5.550 ±(99.9%) 0.019 ms/op
Iteration   1: 5.547 ±(99.9%) 0.021 ms/op
                 existUser·p0.00:   2.154 ms/op
                 existUser·p0.50:   5.202 ms/op
                 existUser·p0.90:   6.912 ms/op
                 existUser·p0.95:   7.995 ms/op
                 existUser·p0.99:   11.111 ms/op
                 existUser·p0.999:  27.289 ms/op
                 existUser·p0.9999: 32.849 ms/op
                 existUser·p1.00:   33.751 ms/op

Iteration   2: 5.629 ±(99.9%) 0.025 ms/op
                 existUser·p0.00:   1.606 ms/op
                 existUser·p0.50:   5.112 ms/op
                 existUser·p0.90:   7.356 ms/op
                 existUser·p0.95:   8.815 ms/op
                 existUser·p0.99:   12.435 ms/op
                 existUser·p0.999:  26.241 ms/op
                 existUser·p0.9999: 32.818 ms/op
                 existUser·p1.00:   33.554 ms/op

Iteration   3: 5.460 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.176 ms/op
                 existUser·p0.50:   5.120 ms/op
                 existUser·p0.90:   6.767 ms/op
                 existUser·p0.95:   7.724 ms/op
                 existUser·p0.99:   10.125 ms/op
                 existUser·p0.999:  16.546 ms/op
                 existUser·p0.9999: 29.725 ms/op
                 existUser·p1.00:   30.867 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 173041
  mean =      5.544 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 71352 
    [ 5.000,  7.500) = 89154 
    [ 7.500, 10.000) = 9246 
    [10.000, 12.500) = 2098 
    [12.500, 15.000) = 646 
    [15.000, 17.500) = 257 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 29 
    [27.500, 30.000) = 65 
    [30.000, 32.500) = 49 
    [32.500, 35.000) = 17 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.176 ms/op
     p(50.0000) =      5.145 ms/op
     p(90.0000) =      6.980 ms/op
     p(95.0000) =      8.159 ms/op
     p(99.0000) =     11.551 ms/op
     p(99.9000) =     22.053 ms/op
     p(99.9900) =     32.486 ms/op
     p(99.9990) =     33.703 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 16.966 ±(99.9%) 0.251 ms/op
# Warmup Iteration   2: 6.684 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 6.031 ±(99.9%) 0.026 ms/op
Iteration   1: 6.195 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   2.523 ms/op
                 getUser·p0.50:   5.603 ms/op
                 getUser·p0.90:   8.421 ms/op
                 getUser·p0.95:   10.043 ms/op
                 getUser·p0.99:   13.304 ms/op
                 getUser·p0.999:  20.021 ms/op
                 getUser·p0.9999: 30.933 ms/op
                 getUser·p1.00:   32.014 ms/op

Iteration   2: 6.420 ±(99.9%) 0.035 ms/op
                 getUser·p0.00:   1.358 ms/op
                 getUser·p0.50:   5.743 ms/op
                 getUser·p0.90:   8.929 ms/op
                 getUser·p0.95:   10.289 ms/op
                 getUser·p0.99:   14.670 ms/op
                 getUser·p0.999:  34.792 ms/op
                 getUser·p0.9999: 43.059 ms/op
                 getUser·p1.00:   43.123 ms/op

Iteration   3: 5.924 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   0.863 ms/op
                 getUser·p0.50:   5.415 ms/op
                 getUser·p0.90:   7.676 ms/op
                 getUser·p0.95:   9.273 ms/op
                 getUser·p0.99:   12.931 ms/op
                 getUser·p0.999:  34.278 ms/op
                 getUser·p0.9999: 41.301 ms/op
                 getUser·p1.00:   42.271 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 155344
  mean =      6.173 ±(99.9%) 0.018 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 31093 
    [ 5.000, 10.000) = 116789 
    [10.000, 15.000) = 6509 
    [15.000, 20.000) = 703 
    [20.000, 25.000) = 56 
    [25.000, 30.000) = 42 
    [30.000, 35.000) = 64 
    [35.000, 40.000) = 71 
    [40.000, 45.000) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      5.562 ms/op
     p(90.0000) =      8.389 ms/op
     p(95.0000) =      9.896 ms/op
     p(99.0000) =     13.631 ms/op
     p(99.9000) =     29.229 ms/op
     p(99.9900) =     40.073 ms/op
     p(99.9990) =     43.123 ms/op
     p(99.9999) =     43.123 ms/op
    p(100.0000) =     43.123 ms/op


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
# Warmup Iteration   1: 20.521 ±(99.9%) 0.412 ms/op
# Warmup Iteration   2: 8.945 ±(99.9%) 0.076 ms/op
# Warmup Iteration   3: 6.904 ±(99.9%) 0.033 ms/op
Iteration   1: 6.489 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.814 ms/op
                 listUser·p0.50:   5.988 ms/op
                 listUser·p0.90:   7.987 ms/op
                 listUser·p0.95:   9.601 ms/op
                 listUser·p0.99:   13.372 ms/op
                 listUser·p0.999:  29.318 ms/op
                 listUser·p0.9999: 32.485 ms/op
                 listUser·p1.00:   33.358 ms/op

Iteration   2: 6.821 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   3.084 ms/op
                 listUser·p0.50:   6.414 ms/op
                 listUser·p0.90:   8.319 ms/op
                 listUser·p0.95:   9.814 ms/op
                 listUser·p0.99:   12.845 ms/op
                 listUser·p0.999:  31.038 ms/op
                 listUser·p0.9999: 39.256 ms/op
                 listUser·p1.00:   40.632 ms/op

Iteration   3: 7.024 ±(99.9%) 0.031 ms/op
                 listUser·p0.00:   3.035 ms/op
                 listUser·p0.50:   6.480 ms/op
                 listUser·p0.90:   9.306 ms/op
                 listUser·p0.95:   10.568 ms/op
                 listUser·p0.99:   14.877 ms/op
                 listUser·p0.999:  26.828 ms/op
                 listUser·p0.9999: 33.640 ms/op
                 listUser·p1.00:   34.406 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 141845
  mean =      6.771 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 3011 
    [ 5.000, 10.000) = 131506 
    [10.000, 15.000) = 6327 
    [15.000, 20.000) = 667 
    [20.000, 25.000) = 49 
    [25.000, 30.000) = 166 
    [30.000, 35.000) = 90 
    [35.000, 40.000) = 26 
    [40.000, 45.000) = 3 

  Percentiles, ms/op:
      p(0.0000) =      2.814 ms/op
     p(50.0000) =      6.291 ms/op
     p(90.0000) =      8.536 ms/op
     p(95.0000) =     10.076 ms/op
     p(99.0000) =     13.910 ms/op
     p(99.9000) =     29.529 ms/op
     p(99.9900) =     38.249 ms/op
     p(99.9990) =     40.495 ms/op
     p(99.9999) =     40.632 ms/op
    p(100.0000) =     40.632 ms/op


# Run complete. Total time: 00:13:23

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.476 ± 1.799  ops/ms
ClientPb.existUser                       thrpt       3   5.710 ± 0.699  ops/ms
ClientPb.getUser                         thrpt       3   5.538 ± 2.688  ops/ms
ClientPb.listUser                        thrpt       3   4.660 ± 1.141  ops/ms
ClientPb.createUser                       avgt       3   5.738 ± 3.992   ms/op
ClientPb.existUser                        avgt       3   5.553 ± 1.847   ms/op
ClientPb.getUser                          avgt       3   5.586 ± 2.882   ms/op
ClientPb.listUser                         avgt       3   6.852 ± 3.228   ms/op
ClientPb.createUser                     sample  169593   5.657 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.413           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.284           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.062           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.036           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.945           ms/op
ClientPb.createUser:createUser·p0.999   sample          20.414           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.787           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.047           ms/op
ClientPb.existUser                      sample  173041   5.544 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.176           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.145           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.980           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.159           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.551           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.053           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.486           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.751           ms/op
ClientPb.getUser                        sample  155344   6.173 ± 0.018   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.863           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.562           ms/op
ClientPb.getUser:getUser·p0.90          sample           8.389           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.896           ms/op
ClientPb.getUser:getUser·p0.99          sample          13.631           ms/op
ClientPb.getUser:getUser·p0.999         sample          29.229           ms/op
ClientPb.getUser:getUser·p0.9999        sample          40.073           ms/op
ClientPb.getUser:getUser·p1.00          sample          43.123           ms/op
ClientPb.listUser                       sample  141845   6.771 ± 0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.814           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.291           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.536           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.076           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.910           ms/op
ClientPb.listUser:listUser·p0.999       sample          29.529           ms/op
ClientPb.listUser:listUser·p0.9999      sample          38.249           ms/op
ClientPb.listUser:listUser·p1.00        sample          40.632           ms/op
