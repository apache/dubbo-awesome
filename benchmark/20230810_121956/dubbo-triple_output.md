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
# Warmup Iteration   1: 2.017 ops/ms
# Warmup Iteration   2: 5.807 ops/ms
# Warmup Iteration   3: 8.518 ops/ms
Iteration   1: 9.080 ops/ms
Iteration   2: 9.025 ops/ms
Iteration   3: 9.125 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.077 ±(99.9%) 0.913 ops/ms [Average]
  (min, avg, max) = (9.025, 9.077, 9.125), stdev = 0.050
  CI (99.9%): [8.163, 9.990] (assumes normal distribution)


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
# Warmup Iteration   1: 3.397 ops/ms
# Warmup Iteration   2: 8.779 ops/ms
# Warmup Iteration   3: 9.236 ops/ms
Iteration   1: 9.621 ops/ms
Iteration   2: 9.690 ops/ms
Iteration   3: 9.500 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.604 ±(99.9%) 1.755 ops/ms [Average]
  (min, avg, max) = (9.500, 9.604, 9.690), stdev = 0.096
  CI (99.9%): [7.848, 11.359] (assumes normal distribution)


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
# Warmup Iteration   1: 3.055 ops/ms
# Warmup Iteration   2: 8.201 ops/ms
# Warmup Iteration   3: 9.080 ops/ms
Iteration   1: 9.333 ops/ms
Iteration   2: 9.240 ops/ms
Iteration   3: 9.396 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.323 ±(99.9%) 1.436 ops/ms [Average]
  (min, avg, max) = (9.240, 9.323, 9.396), stdev = 0.079
  CI (99.9%): [7.887, 10.759] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.693 ops/ms
# Warmup Iteration   2: 7.093 ops/ms
# Warmup Iteration   3: 7.610 ops/ms
Iteration   1: 7.977 ops/ms
Iteration   2: 7.917 ops/ms
Iteration   3: 7.856 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.916 ±(99.9%) 1.104 ops/ms [Average]
  (min, avg, max) = (7.856, 7.916, 7.977), stdev = 0.060
  CI (99.9%): [6.813, 9.020] (assumes normal distribution)


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
# Warmup Iteration   1: 8.875 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.712 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.718 ±(99.9%) 0.005 ms/op
Iteration   1: 3.522 ±(99.9%) 0.004 ms/op
Iteration   2: 3.494 ±(99.9%) 0.007 ms/op
Iteration   3: 3.289 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.435 ±(99.9%) 2.322 ms/op [Average]
  (min, avg, max) = (3.289, 3.435, 3.522), stdev = 0.127
  CI (99.9%): [1.113, 5.757] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 7.998 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.616 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.421 ±(99.9%) 0.006 ms/op
Iteration   1: 3.224 ±(99.9%) 0.003 ms/op
Iteration   2: 3.245 ±(99.9%) 0.003 ms/op
Iteration   3: 3.251 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.240 ±(99.9%) 0.259 ms/op [Average]
  (min, avg, max) = (3.224, 3.240, 3.251), stdev = 0.014
  CI (99.9%): [2.981, 3.500] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.532 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.772 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.465 ±(99.9%) 0.006 ms/op
Iteration   1: 3.473 ±(99.9%) 0.005 ms/op
Iteration   2: 3.399 ±(99.9%) 0.006 ms/op
Iteration   3: 3.441 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.438 ±(99.9%) 0.675 ms/op [Average]
  (min, avg, max) = (3.399, 3.438, 3.473), stdev = 0.037
  CI (99.9%): [2.763, 4.112] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 9.400 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.376 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.136 ±(99.9%) 0.009 ms/op
Iteration   1: 4.072 ±(99.9%) 0.008 ms/op
Iteration   2: 4.112 ±(99.9%) 0.007 ms/op
Iteration   3: 4.122 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.102 ±(99.9%) 0.485 ms/op [Average]
  (min, avg, max) = (4.072, 4.102, 4.122), stdev = 0.027
  CI (99.9%): [3.617, 4.587] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.544 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.940 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.492 ±(99.9%) 0.011 ms/op
Iteration   1: 3.583 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.339 ms/op
                 createUser·p0.50:   3.400 ms/op
                 createUser·p0.90:   4.219 ms/op
                 createUser·p0.95:   4.620 ms/op
                 createUser·p0.99:   6.578 ms/op
                 createUser·p0.999:  18.802 ms/op
                 createUser·p0.9999: 22.479 ms/op
                 createUser·p1.00:   23.953 ms/op

Iteration   2: 3.500 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.647 ms/op
                 createUser·p0.50:   3.379 ms/op
                 createUser·p0.90:   4.014 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   6.423 ms/op
                 createUser·p0.999:  21.046 ms/op
                 createUser·p0.9999: 24.543 ms/op
                 createUser·p1.00:   25.887 ms/op

Iteration   3: 3.416 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.350 ms/op
                 createUser·p0.50:   3.330 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   4.174 ms/op
                 createUser·p0.99:   5.929 ms/op
                 createUser·p0.999:  22.032 ms/op
                 createUser·p0.9999: 25.553 ms/op
                 createUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 274183
  mean =      3.498 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9559 
    [ 2.500,  5.000) = 257109 
    [ 5.000,  7.500) = 5976 
    [ 7.500, 10.000) = 942 
    [10.000, 12.500) = 258 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 121 
    [22.500, 25.000) = 123 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      0.339 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      4.051 ms/op
     p(95.0000) =      4.375 ms/op
     p(99.0000) =      6.342 ms/op
     p(99.9000) =     19.649 ms/op
     p(99.9900) =     24.942 ms/op
     p(99.9990) =     25.928 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 8.585 ±(99.9%) 0.106 ms/op
# Warmup Iteration   2: 3.683 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.344 ±(99.9%) 0.009 ms/op
Iteration   1: 3.524 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.788 ms/op
                 existUser·p0.50:   3.387 ms/op
                 existUser·p0.90:   4.076 ms/op
                 existUser·p0.95:   4.588 ms/op
                 existUser·p0.99:   6.463 ms/op
                 existUser·p0.999:  10.090 ms/op
                 existUser·p0.9999: 22.476 ms/op
                 existUser·p1.00:   29.557 ms/op

Iteration   2: 3.475 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.941 ms/op
                 existUser·p0.50:   3.363 ms/op
                 existUser·p0.90:   4.002 ms/op
                 existUser·p0.95:   4.366 ms/op
                 existUser·p0.99:   6.314 ms/op
                 existUser·p0.999:  24.342 ms/op
                 existUser·p0.9999: 30.133 ms/op
                 existUser·p1.00:   31.359 ms/op

Iteration   3: 3.427 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.848 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   3.658 ms/op
                 existUser·p0.95:   4.190 ms/op
                 existUser·p0.99:   6.501 ms/op
                 existUser·p0.999:  21.062 ms/op
                 existUser·p0.9999: 27.154 ms/op
                 existUser·p1.00:   27.558 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 276114
  mean =      3.475 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17305 
    [ 2.500,  5.000) = 249683 
    [ 5.000,  7.500) = 7682 
    [ 7.500, 10.000) = 890 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 80 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 98 
    [27.500, 30.000) = 27 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.848 ms/op
     p(50.0000) =      3.367 ms/op
     p(90.0000) =      3.961 ms/op
     p(95.0000) =      4.399 ms/op
     p(99.0000) =      6.423 ms/op
     p(99.9000) =     14.690 ms/op
     p(99.9900) =     28.972 ms/op
     p(99.9990) =     30.818 ms/op
     p(99.9999) =     31.359 ms/op
    p(100.0000) =     31.359 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.073 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 3.758 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.436 ±(99.9%) 0.010 ms/op
Iteration   1: 3.672 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.448 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   4.350 ms/op
                 getUser·p0.95:   5.784 ms/op
                 getUser·p0.99:   7.791 ms/op
                 getUser·p0.999:  22.278 ms/op
                 getUser·p0.9999: 33.780 ms/op
                 getUser·p1.00:   34.669 ms/op

Iteration   2: 3.465 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.257 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.863 ms/op
                 getUser·p0.95:   4.456 ms/op
                 getUser·p0.99:   6.693 ms/op
                 getUser·p0.999:  23.453 ms/op
                 getUser·p0.9999: 26.404 ms/op
                 getUser·p1.00:   27.296 ms/op

Iteration   3: 3.459 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.827 ms/op
                 getUser·p0.50:   3.289 ms/op
                 getUser·p0.90:   3.801 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   6.824 ms/op
                 getUser·p0.999:  22.367 ms/op
                 getUser·p0.9999: 27.025 ms/op
                 getUser·p1.00:   27.984 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 271883
  mean =      3.529 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5198 
    [ 2.500,  5.000) = 253624 
    [ 5.000,  7.500) = 10778 
    [ 7.500, 10.000) = 1496 
    [10.000, 12.500) = 376 
    [12.500, 15.000) = 89 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 6 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 103 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 12 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.827 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      7.315 ms/op
     p(99.9000) =     22.352 ms/op
     p(99.9900) =     31.982 ms/op
     p(99.9990) =     34.669 ms/op
     p(99.9999) =     34.669 ms/op
    p(100.0000) =     34.669 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.177 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.407 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.107 ±(99.9%) 0.014 ms/op
Iteration   1: 4.070 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.277 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   4.948 ms/op
                 listUser·p0.99:   7.946 ms/op
                 listUser·p0.999:  19.956 ms/op
                 listUser·p0.9999: 25.130 ms/op
                 listUser·p1.00:   26.280 ms/op

Iteration   2: 4.095 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.343 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.669 ms/op
                 listUser·p0.95:   5.349 ms/op
                 listUser·p0.99:   8.159 ms/op
                 listUser·p0.999:  16.024 ms/op
                 listUser·p0.9999: 20.414 ms/op
                 listUser·p1.00:   20.447 ms/op

Iteration   3: 4.085 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.903 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.547 ms/op
                 listUser·p0.95:   5.022 ms/op
                 listUser·p0.99:   8.454 ms/op
                 listUser·p0.999:  15.614 ms/op
                 listUser·p0.9999: 21.103 ms/op
                 listUser·p1.00:   21.135 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235253
  mean =      4.083 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 43 
    [ 2.500,  5.000) = 222720 
    [ 5.000,  7.500) = 8945 
    [ 7.500, 10.000) = 2409 
    [10.000, 12.500) = 547 
    [12.500, 15.000) = 185 
    [15.000, 17.500) = 195 
    [17.500, 20.000) = 106 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      1.903 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      4.596 ms/op
     p(95.0000) =      5.071 ms/op
     p(99.0000) =      8.319 ms/op
     p(99.9000) =     16.343 ms/op
     p(99.9900) =     24.474 ms/op
     p(99.9990) =     26.006 ms/op
     p(99.9999) =     26.280 ms/op
    p(100.0000) =     26.280 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.077 ± 0.913  ops/ms
ClientPb.existUser                       thrpt       3   9.604 ± 1.755  ops/ms
ClientPb.getUser                         thrpt       3   9.323 ± 1.436  ops/ms
ClientPb.listUser                        thrpt       3   7.916 ± 1.104  ops/ms
ClientPb.createUser                       avgt       3   3.435 ± 2.322   ms/op
ClientPb.existUser                        avgt       3   3.240 ± 0.259   ms/op
ClientPb.getUser                          avgt       3   3.438 ± 0.675   ms/op
ClientPb.listUser                         avgt       3   4.102 ± 0.485   ms/op
ClientPb.createUser                     sample  274183   3.498 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.339           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.367           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.051           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.375           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.342           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.649           ms/op
ClientPb.createUser:createUser·p0.9999  sample          24.942           ms/op
ClientPb.createUser:createUser·p1.00    sample          26.214           ms/op
ClientPb.existUser                      sample  276114   3.475 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.848           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.367           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.961           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.399           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.423           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.690           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.972           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.359           ms/op
ClientPb.getUser                        sample  271883   3.529 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.827           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.310           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.030           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.891           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.315           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.352           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.982           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.669           ms/op
ClientPb.listUser                       sample  235253   4.083 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.903           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.899           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.596           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.071           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.319           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.343           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.474           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.280           ms/op
